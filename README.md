# Ingress-Portals-Bellingham
Geo coordinates of portal locations in and around Bellingham, WA.  Works with [IngressDualMap](https://idm.t.allofti.me/).  Just drop the CSV in a directory named "IngressDualMap" on your SD or internal storage root directory, and import the data from the app to get started.

## Contributing

All data is gathered through the ingress.com/intel page using two userscripts.  Make sure greasemoneky (Firefox) or Tapermonkey (Chrome) are installed, and install the scripts found in the repos below.

* [IITC: Ingress Intel Map Total Conversion](https://github.com/jonatkins/ingress-intel-total-conversion)
* [ITTC plugin: Ingress Dual Map Exporter](https://gist.github.com/OllieTerrance/8547503/raw/dc9663c65e9834cc7f85d0c118999e7df5403836/IngressDualMap.user.js)

1. Take `locations.csv` and open the file in a text editor (such as notepad, gedit, sublime text, etc.).
2.  Navigate to https://www.ingress.com/intel in the browser with the userscripts above.
3.  Zoom into an area of a map where portals are listed.  Make sure it shows "portals: all" in the bottom right corner.  If it says "all links" then you need to zoom in.
4.  Wait until it says `map: done` in the bottom right.
5.  Click `IDM Export` in the lower panel of the top right.
6.  Paste into your local copy of `locations.csv`
7.  Repeat steps 3-6 until you have the desired coverage
8.  Select everything in `locations.csv` and copy it (ctrl+a, ctrl+c)
9.  Paste into [a text sorter](http://textmechanic.com/text-tools/basic-text-tools/sort-text-lines/) and sort alphabetically
10.  Paste that result into [something that removes duplicate lines](http://textmechanic.com/text-tools/basic-text-tools/remove-duplicate-lines/).
11.  Fork this repo and make a pull request by editing the `locations.csv` file listed above this readme.


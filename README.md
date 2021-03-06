![Logo](https://raw.github.com/strohne/Facepager/master/icons/icon_facepager.png)

Facepager was made for fetching public available data from Facebook, Twitter and other JSON-based API. 
All data is stored in a SQLite database and may be exported to csv. 

### News
See the [new features in Version 3.5](https://github.com/strohne/Facepager/releases/tag/v3.5) on the release page. 

### Installer

Installation packages for each versions are available [here](http://www.ls1.ifkw.uni-muenchen.de/personen/wiss_ma/keyling_till/software.html). Database files may be incompatible between versions.
                                                      

###Getting started

1. Click "New Database" in the toolbar to create a blank database
2. Add Facebook IDs by clicking "Add Nodes" in the toolbar. Enter the last part of a Facebook page, e.g. enter "Tatort" for the page "http://www.facebook.com/Tatort". Alternatively you can enter "me" as reference to yourself.
3. Select the Facebook tab and set Query to "<self>"
4. In the Facebook tab click on "Login to Facebook" and login to get a valid access token. Notice: the access token is like a password to Facebook. Since it may be printed in the status log and saved in the application settings don't give anyone untrusted access to your computer or to the status log.
5. Select one or more nodes in the view and click "Fetch data".
6. Click "Expand nodes" in the toolbar and select one of the new child nodes. The raw data is shown to the right.
7. Change the column setup according to your needs by adding keys found in the raw data into the "Custom Table Columns" area. Don't forget to click "Apply Column Setup".
8. For further information, click the "help" button and try the default presets


###Citation

[Keyling, Till](http://www.ls1.ifkw.uni-muenchen.de/personen/wiss_ma/keyling_till/index.html) / [Jünger, Jakob](http://www.phil.uni-greifswald.de/sozial/ipk/mitarbeitende/lehrstuhl-fuer-kommunikationswissenschaft/jakob-juenger.html) (2013). Facepager. An application for generic data retrieval through APIs. Source code available at https://github.com/strohne/Facepager/.

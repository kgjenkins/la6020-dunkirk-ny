# la6020-dunkirk

A subset of data for Dunkirk, NY for an intro to ArcGIS Pro workshop for LA 6020, spring 2023.

More data is available in the Box folder for the class.


Download the workshop data from:  
<https://github.com/kgjenkins/la6020-dunkirk-ny/archive/refs/heads/main.zip>

> **Warning**
>
> Be sure to unzip the downloaded zipfile!
> * Right-click the file > Extract All...

Outline:

* Open ArcGIS Pro, use Map template
* Create project in the `la6020-dunkirk-ny-main` folder that was extracted from the zip file
* Add municipal boundaries
    * symbology
    * identify features
    * attribute table
* Add chautauqua streets
    * compare to basemap
    * symbology: unique values by SHIELD
        * I = interstate
        * R = 
* Add osm-roads
    * compare visually (change symbology for easier comparison)
    * compare data values
* Add parcels
    * symbology: graduated colors by...
        * Yr_Built -- watch out for 0!
        * Total_AV, normalized by STArea
* Add buildings
* Add contour lines
    * Label by ELEVATION
* Export to CAD
    * Analysis tab > Tools > search for "Export to CAD"


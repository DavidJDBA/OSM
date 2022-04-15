# Using and Contributing to Open Historical Map
NOTE:  This document was prepared for the Maptime MileHigh session, April 26, 2022.  The tasks included herein may have already been completed.  But Open Historical Map (OHM) has other very similar needs.  This can be a guide to fulfilling those needs. - David A. Jenne

## Viewing the Slippy Map
The OHM user interfaces are basically the same as in OpenStreetMap (OSM).  By default, when connecting to https://openhistoricalmap.org a map of the world as it was 1900 is presented. Zoom in and out or pan the map to view different locations.  The main difference is the presence of a time slider in the lower right corner.  The control can be slid back and forth to display particular years or the arrows can be used to automate the display.  The bounding years or current year can be adjusted or entered manually.  The toolbar on the right side can be used to zoom the display, show different layers or provide detailed information.

### Follow Along: Corkscrew curve

In the early 1900s Cody Road leading into Yellowstone National Park was constructed with very steep grades.  A corkscrew curve with a bridge known as "Corkscrew Bridge" was part of this road.  In 1928 the East Entrance Road was completed at a higher elevation and more level grade.  This newer road is the one in use today.  The change can be seen in OpenHistoricalMap at https://openhistoricalmap.org/#map=17/44.46056/-110.11589&layers=O&date=1922&daterange=1800,2022.  Click on the forward arrow to see the rendering as it changes.

Move the time slider back to some year between 1906 and 1928.  Select the "Query Features" toolbar entry (arrow with "?") and select Corkscrew Bridge.  Detailed information appears, including images along with the OHM keys and values associated with the map segment.

Most of the tags are the same as those in OSM.  The most notable differences are the start_date and end_date keys.  Those are triggerd and display the associated object when the time slider passes through the specified date.

## Adding a Feature to the Open Historical Map
Adding and editing features is essentially the same as in OSM.  Either the ID or JOSM Editor can be used.  
### Follow Along:  Roosevelt Arch
Roosevelt Arch is a monument constructed at the north entrance to Yellowstone National Park in 1903.  The arch is the idea of Hiram Chittenden, an engineer who also worked on Yellowstone's Grand Loop Road.  More information can be found here:  https://en.wikipedia.org/wiki/Roosevelt_Arch

To add the arch to the Open Historical Map database, use either JOSM or ID.  The example uses JOSM.  

Open JOSM and naviage to Edit > Preferences.  In the left column, select "OSM Server"  and enter the OHM server and your userid/password:

![JOSM server and logon](JOSM_OHM_Login_pref.jpg).

Select an area of interest to include all of Gardner, Montana.

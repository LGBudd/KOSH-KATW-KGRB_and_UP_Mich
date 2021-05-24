# KOSH-KATW-KGRB_and_UP_Mich
Custom NLCD scenery for east central Wisconsin north to and including the Upper Peninsula of Michigan. This includes airports KOSH, KATW, KGRB, KIMT, KESC, KSAW and KCMX.

## License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

The zip archives on the Releases page were created using the TerraGear and TerraGear-GUI programs developed by the FlightGear project. The git repository includes the source data. To download the resulting scenery, go to [to be determined] and download the zip archives.

## Oshkosh, Appleton, Green Bay and Upper Peninsula of Michigan Custom Scenery

Custom scenery for the Oshkosh (KOSH), Appleton (KATW), Green Bay (KGRB) and Upper Peninsula of Michigan Airports, for the FlightGear Flight Simulator. This includes:
- The airports recommended as of October 2020 from the X-Plane Scenery Gateway
- Area includes scenery between the following coordinates: 
  - min lat 43.5
  - max lat 48.0
  - min lon -89.0
  - max lon -87.0 
- Custom Material definitions and Textures for the area to make the land cover more realistic.
- Optional USGS orthophotos around major airports and some smaller airports within the included area.
- Groundnets for the major airports within the area (KATW, KGRB, KCMX) have been uploaded to Terrasync and now are included in the FlightGear database.
- Terrasync objects placed at KOSH, KIMT, KESC, KCMX, KSAW
- OSM2City objects within the area

### NOTE: 
This scenery is best when used together with "Champaign", "KORD-KMKE" and "KOSH-KATW-KGRB_and_UP-Mich" custom scenery. Use of these three custom sceneries together (KORD-KMKE-Custom-Scenery, Champaign-Custom-Scenery and KOSH-KATW-KGRB_and_UP_Mich-Custom-Scenery) will minimize issues at the scenery borders. They also provide a signicant North-South flight area with decent scenery. For the area covered near KOSH (Oshkosh, WI and home of the Experimental Aircraft Association's Convention each year), KORD-KMKE and this custom scenery MUST be used together. 

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/ as of October 2020
- Landcover: National landcover database (NLCD): https://www.usgs.gov/centers/eros/science/national-land-cover-database
- Elevation: Shuttle Radar Topology Mission 1-arc-second (SRTM-1), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: National Hydrography Dataset (NHD): https://www.usgs.gov/core-science-systems/ngp/national-hydrography
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects
- Orthophotos: USGS Orthophotos: https://earthexplorer.usgs.gov/ Credit: U.S. Geological Survey. Color correction done by a first-time amateur.

### To Download

To download the custom scenery files, go to the [to be determined] page and download the zip archives.

## To Install

1. Create a directory on your local hard drive
1. Download Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Terrain.zip, and Orthophotos,zip 
1. Extract the files into the local directory you've created. 

For example, create a directory called "KORD-KMKE" on your computer. Extract the downloaded files into this directory. 

1. Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher) 
1. To use the custom materials definitions and custom textures created:
    a) Download Illinois-data.zip and extract it. Rename the folder to "data.zip".
    b) Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear 2020.4 directory. This should result in Illinois.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "Illinois" in the "$FG_ROOT/Textures/Terrain/" directory.
 1. Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, the click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. 
 1. Make the selections you want to use for your next flight then click "Fly", as usual.
 1. Rendering Options enable OSM buildings, detailed roads and pylons under 

### Commercial and General Aviation Add-on Traffic Files DAL-UP and Gen-UP
Add-on traffic files were generated for the area. The files add daily Delta flights to the UP of Michigan which were not included in the DAL traffic file released with FlightGear up to version 2020.3.8. To install these, simply:
1) Extract the files into a temporary directory of your choosing.
2) Cut the files and paste into the appropriate directory "D" or "G" within the \FlightGear [version]\data\AI\Traffic\ folder.

## Screenshots

### Turn to final approach, KGRB (Austin-Straubel International) (with orthophotos)
![Turn to final, KGRB](https://github.com/LGBudd/KOSH-KATW-KGRB_and_UP_Mich/blob/main/Screenshots/Appr%20to%20KGRB.png)

### Looking East Toward the Downtown Area of Green Bay (with orthophotos)
![Looking East Over Residential Green Bay](https://github.com/LGBudd/KOSH-KATW-KGRB_and_UP_Mich/blob/main/Screenshots/Looking%20East%20%20Over%20Green%20Bay.png)

### Whitman Field, Oshkosh, WI (Home of the EAA) (no orthophotos)
![Whitman Field, Oshkosh, WI](https://github.com/LGBudd/KOSH-KATW-KGRB_and_UP_Mich/blob/main/Screenshots/KOSH.png)

### Timberstone Golf Course, Iron Mountain, MI (with orthophotos)
![Timberstone Golf Course](https://github.com/LGBudd/KOSH-KATW-KGRB_and_UP_Mich/blob/main/Screenshots/Timberstone%20Golf.png)

### Escanaba, Michigan (with orthophotos)
![Escanaba, Michigan](https://github.com/LGBudd/KOSH-KATW-KGRB_and_UP_Mich/blob/main/Screenshots/Escanaba.png)

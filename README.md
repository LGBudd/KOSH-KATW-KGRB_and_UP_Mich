# KOSH-KATW-KGRB_and_UP_Mich
Oshkosh, Appleton, Green Bay and Central Upper Michigan Airports

## This site is Under Construction!

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.

The zip archives on the Releases page were created using the TerraGear and TerraGear-GUI programs developed by the FlightGear project. The git repository includes the source data. To download the resulting scenery, go to the Releases page and download the zip archives.

## Oshkosh, Appleton, Green Bay and Upper Peninsula of Michigan Custom Scenery

Custom scenery for the Oshkosh (KOSH), Appleton (KATW), Green Bay (KGRB) and Upper Peninsula of Michigan Airports, for the FlightGear Flight Simulator. This includes:
- The airports recommended as of October 2020 from the X-Plane Scenery Gateway
- Area includes scenery between the following coordinates: 
  - min lat 43.5
  - max lat 48.0
  - min lon -89.0
  - max lon -87.0 
- Optional USGS orthophotos around major airports and some smaller airports within the included area.
- Groundnets for the major airports within the area (KATW, KGRB, KCMX) have been uploaded to Terrasync and now are included in the FlightGear database.
- Terrasync objects placed at KOSH, KIMT, KESC, KCMX, KSAW
- OSM2City objects within the area

### NOTE: 
This scenery is best when used together with "Champaign" and "Oshkosh and UP" custom scenery. Use of these three custom sceneries together (KORD-KMKE-Custom-Scenery, Champaign-Custom-Scenery and NWI-UPM-Custom-Scenery) will minimize issues at the scenery borders. They also provide a signicant North-South flight area with decent scenery.

### Data Sources

- Airports: X-Plane Scenery Gateway: https://gateway.x-plane.com/ as of October 2020
- Landcover: National landcover database (NLCD): https://www.usgs.gov/centers/eros/science/national-land-cover-database
- Elevation: Shuttle Radar Topology Mission 1-arc-second (SRTM-1), void-filled version: https://earthexplorer.usgs.gov/
- Rivers and waterbodies: National Hydrography Dataset (NHD): https://www.usgs.gov/core-science-systems/ngp/national-hydrography
- Buildings, roads, pylons, other objects: OpenStreetMap using osm2city: https://www.openstreetmap.org/ https://osm2city.readthedocs.io/en/latest/
- FlightGear TerraSync objects
- Orthophotos: USGS Orthophotos: https://earthexplorer.usgs.gov/

### To Download

To download the custom scenery files, go to the Releases page and download the zip archives.

## Installation

To install:
1) Create a directory on your local hard drive
2) Download Buildings.zip, Objects.zip, Pylons.zip, Roads.zip, Terrain.zip, and Orthophotos,zip 
3) Extract the files into the local directory you've created. 

For example, create a directory called "KORD-KMKE" on your computer. Extract the downloaded files into this directory. 

4) Add this directory to Additional Scenery Folders in the FlightGear GUI (launcher) 
5) To use the custom materials definitions and custom textures created:
    a) Download Illinois-data.zip and extract it. Rename the folder to "data.zip".
    b) Copy this "data" folder, open "$FG_ROOT" and paste. In Windows, this is the data folder within the FlightGear 2020.4 directory. This should result in Illinois.xml residing in the "$FG_ROOT/Materials/regions/" directory and a folder labeled "Illinois" in the "$FG_ROOT/Textures/Terrain/" directory.
 6) Start FlightGear. While on the start-up screen click "Add-ons". Scroll to the "Additional scenery folders" section, the click the plus (+) sign on the right side of the screen. A dialog box will pop up. Browse to the folder you created in step 1. Highlight the folder, then click "Select Folder". Confirm that the folder was added to the bottom of "Additional scenery folders". You can now highlight and move the folder to a higher priority if necessary. 
 7) Make the selections you want to use for your next flight then click "Fly", as usual.
 8) Rendering Options enable OSM buildings, detailed roads and pylons under 

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LGBudd/NLCD-Terrain/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

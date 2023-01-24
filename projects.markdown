---
layout: page
title: Projects
permalink: /projects/
sitemap: false
---

Here are various personal projects I've developed; the source code can be viewed on my Github page: <a href="https://github.com/juha-toiv">https://github.com/juha-toiv</a>.

### Custom Geoprocessing Tools for ArcGIS Pro

#### Send Location to WhatsApp

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/whatsapp.PNG">

<a href="https://github.com/juha-toiv/send-location-to-whatsapp"><img src="https://gh-card.dev/repos/juha-toiv/send-location-to-whatsapp.svg"></a>
<br>
* Sends geographic coordinates of a point feature layer on ArcGIS Pro to a WhatsApp number via Facebook API
* Recipient receives a location pin which can be viewed with Google Maps on a mobile device
* Input point feature layer must have only one record
* Input point feature can be either projected or geograhic, but must be either WGS 1984 or NAD 1983
<br>
<br>

#### Batch Rename Workspace

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/rename.PNG">

<a href="https://github.com/juha-toiv/batch-rename-workspace"><img src="https://gh-card.dev/repos/juha-toiv/batch-rename-workspace.svg"></a>
<br>
* Custom geoprocessing tool / script for ArcGIS Pro for renaming all feature datasets, feature classes, and field names in a file geodatabase
* User can specify which datasets or fields are renamed by regular expression
* Options to convert dataset or field names to lower case, upper case, title case; or add a prefix or suffix, or replace strings
<br>
<br>

#### Convert 2D Polyline to 3D Polyline

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/polyline.png">

<a href="https://github.com/juha-toiv/convert-2d-polyline-to-3d-polyline"><img src="https://gh-card.dev/repos/juha-toiv/convert-2d-polyline-to-3d-polyline.svg"></a>
<br>
* Converts a 2d polyline to a 3d polyline based on values on a surface raster
* Input polyline feature must have only one record
<br>
<br>

#### XYZ Coordinates to Point

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/xyz_point.png">

<a href="https://github.com/juha-toiv/xyz-coordinates-to-point"><img src="https://gh-card.dev/repos/juha-toiv/xyz-coordinates-to-point.svg"></a>
<br>
* Custom geoprocessing tool / script for a ArcGIS Pro for creating point feature classes or layers from X, Y and Z coordinates (decimal degrees)
* User can specify the output coordinate system
* Output point feature is added to active map, and stored as a shapefile on into a file geodatabase
<br>
<br>

#### Find Coordinate System

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/coordinate.png">

<a href="https://github.com/juha-toiv/find-coordinate-system"><img src="https://gh-card.dev/repos/juha-toiv/find-coordinate-system.svg"></a>
<br>
* Custom geoprocessing tool for ArcGIS Pro to help find the correct coordinate system for a vector feature layer; for example a shapefile missing spatial reference
* Tries different coordinate systems for a vector feature layer
* Output layers are added to active map and saved into a file geodatabase
<br>
<br>

#### Polyline Travel Time

<a href="https://github.com/juha-toiv/polyline-travel-time"><img src="https://gh-card.dev/repos/juha-toiv/polyline-travel-time.svg"></a>
<br>
* Custom geoprocessing tool / script for ArcGIS Pro to calculate an estimated travel time for a polyline feature layer based on average speed and coordinate system
* Modifies the input feature class by adding a new field
<br>
<br>


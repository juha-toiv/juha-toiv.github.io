---
layout: page
title: Projects
permalink: /projects/
sitemap: false
---

Here are various personal projects I've been working on; the source code can be viewed on my Github page: <a href="https://github.com/juha-toiv">https://github.com/juha-toiv</a>.

<h3 style="color:#77BFC7;font-weight: bold;">Custom Geoprocessing Tools for ArcGIS Pro</h3>


#### Convert 2D Polyline to 3D Polyline

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/polyline.png">

<a href="https://github.com/juha-toiv/convert-2d-polyline-to-3d-polyline"><img src="https://gh-card.dev/repos/juha-toiv/convert-2d-polyline-to-3d-polyline.svg"></a>
<br>
* Converts a 2d polyline to a 3d polyline based on values on a surface raster
* Input polyline feature must have only one record
<br>
<br>

#### Coordinates to Point Feature

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/coordinates-to-point.PNG">

<a href="https://github.com/juha-toiv/coordinates-to-point-feature"><img src="https://gh-card.dev/repos/juha-toiv/coordinates-to-point-feature.svg"></a>
<br>
* Custom geoprocessing tool/script for a ArcGIS Pro for creating point feature layers from coordinates in DMS format, or other coordinate notation formats supported by ArcGIS Pro
* Output point feature layer is stored in memory and added to the active map
<br>
<br>

#### Send Coordinates to WhatsApp

<img height="30%" width="30%" style="float:right;padding-left:15px" src="{{site.baseurl}}/assets/images/whatsapp.PNG">

<a href="https://github.com/juha-toiv/send-location-to-whatsapp"><img src="https://gh-card.dev/repos/juha-toiv/send-location-to-whatsapp.svg"></a>
<br>
* Script allows sending location coordinates of a point feature layer from ArcGIS Pro to WhatsApp via Facebook API. The receipient receives a location pin that can be viewed with google maps. 
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

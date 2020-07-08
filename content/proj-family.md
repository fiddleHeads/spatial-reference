---
layout: default
title: Map Projections
nav_order: 5
has_children: true
---

## Map Projections

Let's revisit the main takeaways about projections that we learned from the video at the beginning of class. 

See if you can answer the questions below before you reveal the correct answer by clicking on the arrow.

<details>
<summary>A projection is a mathematical equation to flatten data from a 3D surface onto a ____ plane. </summary>
<br>
2D.
</details>

<details>
<summary>All projections accurately represent the sizes of the continents. True or false. </summary>
<br>
False. Every projection is distorted in some way, and some distort the sizes of different land masses a lot.
</details>

<details>
<summary>Web maps generally use a particular projection. What is it and do you remember why it is used?</summary>
<br>
Most web maps, such as Google maps, use the Mercator projection, often referred to as Web Mercator. It preserves direction, north is always up, and 90 degree turns appear as right angles. It's also good for generating map tiles because it projects the world into a square evenly subdivided across zoom levels.
</details>

![mercator](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/mercator.jpg)

The mercator projection has a hegemonic hold on most web map applications.

If you are using ArcGIS Online, for example, you may encounter difficulties trying to upload any data that is not projected in Web Mercator.

### Terminology

Remember latitutde and longitude? In the context of projections, it may be useful to think of these as lines that have another name to describe them.

Lines of latitude are also called parallels and run east-west parallel to the equator.

Lines of longitude are called meridians and run north-south between the North and South Poles.

![meridian](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/meridian.jpg)

Map projections are typically categorized into three different types, based on the visualization of light shining through through the earth onto a surface, where the surface is a plane, a cylinder, or a cone, respectively.

![lightSource.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/lightSource.jpg)

This visualization is supposed to make projection easier to understand, although I confess it has never worked that well for me. There are also those who [recommend](https://en.wikipedia.org/wiki/Map_projection#Projections_by_surface) dispensing with these categories because they don't account for all projections and lead to misunderstanding and confusion.

Nevertheless, these three categories can be useful models for illustrating some map projections.

### Planar Projections

![planar.jpg](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/planar.jpg)

- these are used most often to map polar regions
- also known as azimuthal projection
- 

### Cylindrical Projections

![cylindrical](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/cylindrical.jpg)

- The Mercator projection is a cylindrical projection.

### Conical Projections

![conic](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/conic.jpg)

This section references ideas and images from [Wikipedia](https://en.wikipedia.org/wiki/Map_projection#Projections_by_surface), [Projected Coordinate Systems](https://mgimond.github.io/Spatial/coordinate-systems.html#projected-coordinate-systems), [Understanding Map Projections](https://kartoweb.itc.nl/geometrics/Map%20projections/Understanding%20Map%20Projections.pdf), [Light Source Metaphor](https://www.mdpi.com/2220-9964/8/4/162/pdf)

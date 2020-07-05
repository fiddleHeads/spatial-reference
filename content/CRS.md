---
layout: default
title: Coordinate Reference System
nav_order: 5
has_children: true
---

## Coordinate Reference Systems

Now I'm going to complicate things a bit by introducing the term **coordinate reference system (CRS),** of which projections are a part.

Let's break down the term a bit.

You're all familiar with a coordinate system from 7th grade geometry, which defines a location in 2-dimensional space on an XY axis.

![cartesian](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/555px-2D_Cartesian_Coordinates.svg.png)

So, what's the problem?

We live on a 3-diminesional earth that is neither perfectly round nor perfectly spherical. The shape of the earth can more accurately be described as an ellipsoid.

So we need a coordinate system that adapts to the Earth's shape.

A **CRS** does this by defining the translation between a location on the earth and that location on a flattened, 2 dimensional coordinate system. 

A **CRS** comprises:

- **Coordinate system**: XY grid
- **Horizontal and vertical units**: units used to define the grid along XY(and Z) axis
- **Datum**: A model of the earth
- **Projection**: mathematical equation used to project objects on the surface of the earth onto a flat surface, i.e. a paper map or a computer screen.

![cartesianSpherical](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/cartSpherical.jpg)

At this point you might be wondering what a datum is. We'll address this in the next section before we go on to talk about two different kinds of coordinate systems used in geospatial software.






This section references ideas, phrases, and images from [Earth Lab](https://www.earthdatascience.org/courses/use-data-open-source-python/intro-vector-data-python/spatial-data-vector-shapefiles/intro-to-coordinate-reference-systems-python/), [pbc GIS](http://pbcgis.com/projection_fundamentals/), and [ArcGIS Blog](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/coordinate-systems-difference/#spatial).
---
layout: default
title: Datums
nav_order: 2
parent: Coordinate Reference System
---

## Datums

So just what is a datum?

Remember that the earth is an ellipsoid. 

A datum mathematically defines the shape and size of the ellipsoid and it's orientation in space.

Measurements of the surface of the earth in different places collected over time by surveyors are used to define a geodetic datum.

Another way to think about datums is that they are a reference for a starting point against which to determine other horizontal or vertical measurements.

For example, a datum ensures that engineers, surveyors, planners, and mapmakers are all starting at the same “zero” elevation. 

![surveyor](https://raw.githubusercontent.com/fiddleHeads/map-projections/master/images/canadianSurveyors.jpg)

### Horizontal and Vertical Datums

A **horizontal** datum measures positions on the surface of the Earth using latitude and longitude.

> A horizontal datum is used to monitor the movement of the Earth's crust, or in other words, to monitor earthquake activity.

> Horizontal datums are also used with geospatial data. All geospatial data should have a defined horizontal datum.

A **vertical** datum defines the height either above or below a nationally defined reference surface (e.g., mean sea level).

> Not all geospatial data needs to have a defined vertical datum, but it makes sense if you are using survey data in a GIS.


### A Brief History of Datums

This history varies according to country.

Although Canada and the U.S.A. have different surveying histories, they have used the same datum since 1913 because they are on the same continent, along with Mexico. 

Who can guess 

<details>
<summary>Who can guess the name of each of the datums used by Canada, the U.S.A., and Mexico since 1913?</summary>
<br>
North American.
</details>

The first 

To learn more about Canada's unique history of surveying, check out [100 Years of Geodetic Surveys in Canada](https://www.nrcan.gc.ca/earth-sciences/geomatics/canadian-spatial-reference-system-csrs/100-years-geodetic-surveys-canada/9110).

Because our understanding of the shape of the surface of the earth has improved over time, we are able to collect ever more accurate and precise measurements.

This is also why datums are evolving and why it is important to use the most up-to-date datum when defining the spatial reference system of your data.

In some case, however, you may be using data that was collected or created using a different datum, and you




In the next section, we'll explore two different kinds of coordinate systems that are used in map making, geographic and projected coordinate systems.

This section references information and ideas from [What is a datum](https://oceanservice.noaa.gov/facts/datum.html), [NOAA Celebrates 200 Years](https://celebrating200years.noaa.gov/magazine/vertical_datums/welcome.html#network), and [Geodetic Datums](https://gisgeography.com/geodetic-datums-nad27-nad83-wgs84/).

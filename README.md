# Length of a polygon

Imagine a client wants to know the "length" of some polygon-shaped structure&mdash;for example a continuous vegetation patch of some wild plant they want to harvest or an oil field they want to exploit. What even is "length of a polygon" in this context and how do you calculate it?
In this notebook, I coded up a solution based on the topological skeleton of a polygon. A toopological skeleton of a shape ["is a thin version of that shape that is equidistant to its boundaries"](https://en.wikipedia.org/wiki/Topological_skeleton). As such, the longest path in a graph representation of a skeleton can be taken as the "length" of that shape.

The problem is based on an interview question that got me thinking and I ended up writing this notebook afterwards.

Uses:
- Python geodata stack including Shapely, Geopandas, GDAL/OGR
- skimage/skan for image shape analysis

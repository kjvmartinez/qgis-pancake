# CLASSIFYING VECTOR DATA

Classifying vector data allows you to assign different symbols to features (different objects in the same layer), depending on their attributes. This allows someone who uses the map to easily see the attributes of various features.  

# Vector Attribute Data

Vector data is arguably the most common kind of data in the daily use of GIS. The vector model represents the location and shape of geographic features using points, lines and polygons (and for 3D data also surfaces and volumes), while their other properties are included as attributes (often presented as a table in QGIS).  

Up to now, none of the changes we have made to the map have been influenced by the objects that are being shown.  

In other words, all the land use areas look alike, and all the roads look alike. When looking at the map, the viewers don’t know anything about the roads they are seeing; only that there is a road of a certain shape in a certain area.  

But the whole strength of GIS is that all the objects that are visible on the map also have attributes. Maps in a GIS aren’t just pictures. They represent not only objects in locations, but also information about those objects.  

The goal for this lesson: To learn about the structure of vector data and explore the attribute data of an object

## Viewing Layer Attributes

It’s important to know that the data you will be working with does not only represent where objects are in space, but also tells you what those objects are.  

The polygons representing the protected areas constitute the spatial data, but we can learn more about the protected areas by exploring the attribute table.  

A row is called a record and is associated with a feature in the Canvas Map, such as a polygon. A column is
called a field (or an attribute), and has a name that helps describe it, such as name or id. Values in the cells
are known as attribute values. These definitions are commonly used in GIS, so it is good to become familiar
with them.  

In the protected_areas layer, there are two features, which are represented by the two polygons we see
on the Map Canvas.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/19%20Viewing%20Layer%20Attributes.gif)


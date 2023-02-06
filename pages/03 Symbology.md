# Symbology

## Changing Color

Let’s begin by changing the color of the landuse layer.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/08%20Changing%20Colors.gif)

**Try yourself 03.01**

Change the color of the water layer to light blue.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/09%20Changing%20Symbol%20Structure.gif)

**Try yourself 03.02**
* Change the water layer’s symbology again so that it has a darker blue outline.
* Change the rivers layer’s symbology to a sensible representation of waterways.

Remember: you can use the Open the Layer Styling panel button and see all the changes instantly. That panel also allows you to undo individual changes while symbolizing a layer.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/10%20Layer%20Styling%20Panel.gif)

## Scale-Based Visibility

Sometimes you will find that a layer is not suitable for a given scale. For example, a dataset of all the continents may have low detail, and not be very accurate at street level. When that happens, you want to be able to hide the dataset at inappropriate scales.

In our case, we may decide to hide the buildings from view at small scales.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/11%20Scale-Based%20Visibility.gif)

## Adding Symbol Layers

Now that you know how to change simple symbology for layers, the next step is to create more complex symbology.
QGIS allows you to do this using symbol layers.


![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/12%20Adding%20Symbol%20Layers.gif)

**Try yourself 3.03**

Remembering to zoom in if necessary, create a simple, but not distracting texture for the buildings layer using the
methods above.

Customize your buildings layer as you like, but remember that it has to be easy to tell different layers apart on the map.

## Ordering Symbol Levels

When symbol layers are rendered, they are also rendered in a sequence, similar to the way the different map layers
are rendered. This means that in some cases, having many symbol layers in one symbol can cause unexpected results.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/13%20Ordering%20Symbol%20Levels.gif)

Well, roads have now a street like symbology, but you see that lines are overlapping each others at each cross. To prevent this from happening, you can sort the symbol levels and thereby control the order in which the different
symbol layers are rendered.

![](https://github.com/kjvmartinez/qgis-pancake/blob/master/gifs/14%20Ordering%20Symbol%20Levels.gif)


**Try yourself 3.04**

Change the appearance of the roads layer again. Make the roads narrow and yellow, with a thin, pale gray outline and a thin black line in the middle.

![ty3.04](https://github.com/kjvmartinez/qgis-pancake/blob/master/imgs/03-04.png)

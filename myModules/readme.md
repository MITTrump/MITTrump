This sample shows how to use the InfoWindowBase class to create a custom info window. This class was introduced at version 2.2 of the ArcGIS API for JavaScript and provides the ability to extend the info window to customize the behavior and appearance of an info window.

In this example, the content of the info window expands when you click the down arrow and the info window is hidden when the map is panned. To build a custom info window with this functionality, extend the InfoWindowBase class and add a new button to the title bar. When the user clicks the down button, the content portion of the info window is displayed using an animated effect defined using the dojo.fx.Toggler class.

After creating the custom info window, you can associate it with the map using the new infoWindow option.

**The source of this folder: [https://developers.arcgis.com/javascript/3/jssamples/widget_extendInfowindow.html](https://developers.arcgis.com/javascript/3/jssamples/widget_extendInfowindow.html)**

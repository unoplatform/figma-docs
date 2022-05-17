# Images

## How to Use Images

Images are a key feature in most modern applications. This release changes the way we handle images in the Uno Figma plugin and offers more flexibility to designers and developers when using images through the Toolkit. It is no longer required to use the Image component from earlier versions of the Toolkit, you may now use images directly into your designs and they will be represented in the plugin’s Preview and code tabs.

### New features
* Previewing placed images no longer requires using Image components which will be deprecated;
* Plugin preview in actual size;
* Set independent corner radius for each image frame corner;
* Figma’s Fit and Fill modes are support both in layout preview and XAML generation.

### Guidelines
* Images are represented by placeholders in the plugin’s Preview tab;
* If you are using an older version of the Figma Uno Toolkit Image components are still supported in the current version of the plugin;
* Figma’s Crop and Tile Image framing modes are not currently supported by the plugin, you may use the functions but not corresponding XAML will be generated;
* Tip: place a copy of your images within the Image Export Templates of the Theme page the toolkit to simplify your exporting workflow.
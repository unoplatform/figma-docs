# How to use Lists

## Overview

If your design requires a dynamic list (lists populated with various data returned by an API) use this component: **List Items: Preset Product list**, it can be found in the *Assets* section of the Toolkit. If your list is static you can build it with components like *Button* and/or *Text Block* components.

### Steps

1. Place *List* inside the `◇ Contente Scrollable` layer of your page template;
2. Select Item variants;
3. Set list related settings in the Uno Plugin. (See below)

*ListItems* have many available variants to choose from: Leading Items, Content, Primary Controls, Secondary Controls or Trailing items. Each of those also have variants of their own e.g. Leading Item can be either: Image, Person Picture or Icon.


![ListItem Variants.png](assets/lists-variants.png)

## Uno Plugin Settings for Lists

To render properly List require specific settings to be enabled in the plugin:

1. Select your *List Items* component in the layout;
2. Launch plugin;
3. Form the *Properties* tab of the plug in (first from the left) select *Layout type* and set it to *List* then click *the Save button (bottom left);
4. Form the *Settings* Tab (far right) Toggle *Binding* to *On* and click the *Save* button (scroll all the way down to find it).
5. Click the Preview* Tab (Second from the left) to render the results, you may have to click the refresh button.

**Note**: Only the first *List Item* displayed at the top of your list generates unique XAML styling.

### Lists with Swipeable Content

To add swipeable lists to your app use **Swipe Control: Preset Product List** found in the assets panel. You can add any number of of items to the list by duplicating `◇ SwipeControl` and `◇ Divider` layers found within the component.

![](assets/lists-swipeable.png)

### Steps

1. Place *Swipe Control: Preset Product List* inside the *Contente Scrollable* layer of your page template;
2. Select Item variants
3. Set related settings in the Uno Plugin. (See below)

### Uno Plugin Settings for Swipeable Lists

To render properly Swipeable List require specific settings to be enabled in the plugin:

1. Select your *Swipe Control: Preset Product List* component in the layout;
2. Launch plugin;
3. Form the *Properties* tab of the plug in (first from the left) select *Layout type* and set it to either *Default or Scrollable* then click *the Save button (bottom left);
4. Click the Preview* Tab (Second from the left) to render the results, you may have to click the refresh button.

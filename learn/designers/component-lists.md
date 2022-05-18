# How to use Lists

## Overview

When the design requires a dynamic list (lists populated with various data returned by an API), use this component: **List Items: Preset Product list**. It can be found in the *Assets* section of the Toolkit. If the list is static, it can be built using components like *Button* and/or *Text Block* components.

### Steps

1. Place *List* inside the `◇ Content Scrollable` layer of the page template;
2. Select Item variants;
3. Set list-related settings in the Uno Plugin. (See below)

*ListItems* have many available variants to choose from: Leading Items, Content, Primary Controls, Secondary Controls, or Trailing items. Each of those also has variants of its own e.g. Leading Item can be either: Image, Person Picture or Icon.


![ListItem Variants.png](assets/lists-variants.png)

## Uno Plugin Settings for Lists

To render properly, List requires specific settings to be enabled in the plugin:

1. Select the *List Items* component in the layout;
2. Launch plugin;
3. Form the *Properties* tab of the plugin (first from the left) select *Layout type* and set it to *List* then click the *Save* button (bottom left);
4. Form the *Settings* Tab (far right) Toggle *Binding* to *On* and click the *Save* button (scroll all the way down to find it).
5. Click the *Preview* Tab (Second from the left) to render the results. It may be required to click the *refresh* button.


>[!NOTE]
>
>Only the first item (usually a *List Item*) at the top of the list will be used to create the template in the generated XAML ouput by the Uno Plugin.

### Lists with Swipeable Content

To add swipeable lists to an app, use the **Swipe Control: Preset Product List** found in the assets panel. Any number of items can be added to the list by duplicating the `◇ SwipeControl` and `◇ Divider` layers found within the component.

![](assets/lists-swipeable.png)

### Steps

1. Place *Swipe Control: Preset Product List* inside the *Content Scrollable* layer of the page template;
2. Select Item variants
3. Set related settings in the Uno Plugin. (See below)

### Uno Plugin Properties for Swipeable Lists

To render properly, Swipeable List requires specific settings to be enabled in the plugin:

1. Select *Swipe Control: Preset Product List* component in the layout;
2. Launch plugin;
3. From the [*Properties* tab](../developers/properties-tab.md) of the plugin (first from the left) select *Layout type* and set it to either *Default or Scrollable* then click the *Save* button (bottom left);
4. Click the *Preview* Tab (Second from the left) to render the results, It may be required to click the *refresh* button.

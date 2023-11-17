---
uid: Uno.Figma.Learn.Designers.Component.Lists
---

# How to Use Lists

## Overview

When the design requires a dynamic list (lists populated with data returned by an API), use the **List: Template** component. It can be found in the *Assets* section of the Toolkit. If the list you need is a static set of elements, build it using components like *Button* and/or *Text Block*.

### Steps

1. Place the *List Template* inside the `◇ Content Scrollable` layer of the page template.
2. With the list selected, right-click and select "Detach Instance" from the contextual menu.
3. Choose the ListItem variants required for your list.
4. Set list-related settings in the Uno Plugin. (See below)

Lists are composed of *ListItems*. *ListItems* have many variants to choose from: Leading Items, Content, Primary Controls, Secondary Controls, or Trailing items. Each of these also has variants of their own, e.g., Leading Item can be either: Image, Person Picture, or Icon.

>[!NOTE]
>Lists do not include space between ListItems. If the design requires space between items, add padding at the top or bottom of your ListItem component.

![ListItem Variants.png](assets/lists-variants.png)

## Uno Plugin Settings for Lists

To render properly, a list requires specific settings to be enabled in the plugin:

1. Select the *List Template* component in the layout.
2. Launch the plugin.
3. From the *Properties* tab of the plugin (first from the left), select *Layout Type* and set it to *Scrollable*. Then click the *Save* button (bottom left).
4. From the *Settings* Tab (far right), toggle *Binding* to *On* and click the *Save* button (scroll all the way down to find it).
5. Return to the *Preview* Tab (second from the left) and click the *Refresh* button to render the results.

>[!NOTE]
>Only the first item (usually a *List Item*) at the top of the list will be used to create the template in the generated XAML output by the Uno Plugin.

### Lists with Swipeable Content

To add swipeable lists to an app, use the **Swipe Control List: Template** found in the assets panel. Any number of items can be added to the list by duplicating the `◇ SwipeControl` and `◇ Divider` layers found within the component.

![](assets/lists-swipeable.png)

### Steps

1. Place the *Swipe Control List: Template* inside the *Content Scrollable* layer of the page template.
2. Choose the SwipeControl variants required for your list.
3. Go to the *Prototype Tab* found in the top right of the Figma interface.
4. Select *Overflow Scrolling*, then select one of the 4 available options:
   - No Scrolling
   - Horizontal Scrolling
   - Vertical Scrolling
   - Horizontal and Vertical Scrolling

### Uno Plugin Properties for Swipeable Lists

To render properly, a Swipeable List requires specific settings to be enabled in the plugin:

1. Start after **Step 2** of the previous section.
2. Select the *Swipe Control List: Template* component in the layout.
3. Launch the plugin.
4. From the [*Properties* tab](../developers/properties-tab.md) of the plugin (first from the left), select *Layout Type* and set it to either *Default* or *Scrollable*, then click the *Save* button (bottom left).
5. Return to the *Preview* Tab (second from the left) and click the *Refresh* button to render the results.

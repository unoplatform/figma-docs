---
uid: Uno.Figma.Learn.Designers.Component.Lists
---

# How to Use Lists in Uno Figma Toolkit

## Overview

Lists are a fundamental element in UI design, used for displaying a series of items. The Uno Figma Toolkit provides the **List: Template** component for dynamic lists, which are especially useful when populating lists with data returned by an API. For static lists, you can construct them using basic components like *Button* and *Text Block*. Additionally, the *ItemsRepeater* can be an effective alternative for both dynamic and static lists, offering flexible layout options.

### Steps for Using List Template

1. Place the *List Template* inside the `◇ Content Scrollable` layer of your page template.
2. Detach the instance of the list for customization.
3. Select appropriate ListItem variants for your list.
4. Configure list-related settings in the Uno Plugin as detailed below.

Lists consist of *ListItems*, which come in various forms like Leading Items, Content, Primary Controls, Secondary Controls, or Trailing items, each with their own set of variants.

![ListItem Variants](assets/lists-variants.png)

> [!NOTE]
> Lists do not inherently include space between items. Add padding to ListItems if spacing is required.

## Uno Plugin Settings for Lists

Proper rendering of lists requires specific settings within the Uno Plugin:

1. Select your *List Template* in the layout.
1. Open the Uno Plugin.
1. Refresh the preview to see the updated list.

> [!CAUTION]
> *Bindings* mode must be enabled in the settings and a *DataContext* must be defined
> for the feature to work.
>
> [!NOTE]
> The first item in the list is typically used to create the template in the generated XAML output.

### Incorporating Swipeable Content in Lists

For interactive lists with swipeable items, use the **Swipe Control List: Template**.

### Steps

1. Insert the *Swipe Control List: Template* within the *Content Scrollable* layer.
2. Choose the required SwipeControl variants.
3. In the *Prototype Tab* (in Figma, not the plugin), select your preferred *Overflow Scrolling* option.

![Swipeable Lists](assets/lists-swipeable.png)

## Alternative: Using ItemsRepeater for Lists

The [*ItemsRepeater*](items-repeater.md), particularly used with the "UniformGridLayout" option, is an excellent alternative for creating both dynamic and static lists. It provides more layout flexibility compared to traditional list templates and is suitable for various design scenarios.

By utilizing these tools and steps, you can effectively implement different types of lists in your designs using the Uno Figma Toolkit, enhancing the functionality and visual appeal of your UI.

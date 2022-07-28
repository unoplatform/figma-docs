# How to Use Uno Platform Toolkit and Plugin

## Links

The plugin is required to follow instructions in this section. Installation instructions are available in the [download page](../../download.md).

## Overview

Uno Figma Toolkit (UFT) and Uno Plugin allow to accelerate the designer to developer handoff by generating XAML code straight from the high fidelity designs.

UFT comes stocked with Components, Text and color styles that are automatically recognized by the plugin and converted directly to XAML. Designers can also get a live preview of the translated look, behavior and code from their work in just a few seconds.

The plugin functionalities have been organized into 6 main tabs: [Properties](properties-tab.md), [Preview](preview-tab.md), [XAML](xaml-tab.md), [Themes](themes-tab.md), [DataContext](datacontext-tab.md) and [Settings](settings-tab.md).

## General Plugin Guidelines

- Most of the features in the plugin requires that at least one layer in the document to be selected;
- To get the full power of the plugin, **it is highly recommended to start by duplicating the Uno Figma Toolkit**. Not doing so will prevent the plugin from recognizing its native components and styles;
- Depending on settings, it may be required to click the refresh button in the plugin to view results;
- *Properties* tab allows to impart behaviors and bindings to components;
- *Preview* tab allows the visualization of the generated XAML;
- *XAML* tab allows to inspect, edit, copy and export the generated code;
- *Themes* tab allows to inspect and copy to pasteboard the resource dictionary;
- *DataContext* tab allows to set mocked data for binding in the *Preview* tab;
- Properties, Themes, Data Context and Settings tabs all require saving changes before they can be applied.

> [!NOTE]
> The generation of the XAML and the preview of it is a resource expensive operation and can take some time to complete.

## About the Layout (Auto Layouts)

The **Auto Layout** is the basis of the plugin. For any other components to be displayed as intended, they must be put in a **Auto Layout**.

> **Binding:** By default, Data set with the **Content** field in the **Properties** tab in the plugin will be applied to the *DataContext* property of the Auto Layout.



| Property             | Options                       | Description                                                  |
| -------------------- | ----------------------------- | ------------------------------------------------------------ |
| Orientation          | `Horizontal, Vertical`        | Changes how the components in the Auto Layout will be displayed, they will be stacked horizontally or vertically. |
| Spacing              | `<value>`                     | Sets the distance between the items. The value that will be set in the plugin will be the **Spacing between items** value. |
| Justify              | `Stack, SpaceBetween`         | The *Stack* option will set all the items one after the other with only the **Spacing** between the items. The *SpaceBetween* option will automatically set the distance between all the items in the Auto Layout. In Figma the options will be displayed as **Packed** and **Space between** in the **Spacing mode** category. |
| PrimaryAxisAlignment | `Start, Center, End, Stretch` | Sets how the items will be aligned in the Auto Layout. This Property is heavily affected by the *Orientation* property. For example, *Start* will align the list to the left (Horizontal Orientation) or to the top (Vertical Orientation) |
| PrimaryAlignment     | `Auto, Stretch`               | Changes how much space an item will take. *Auto* will make the item only take the required amount of space, *Space* will make the item take all the space it can. Both options only affect the *Orientation*'s side. |
| CounterAlignement    | `Start, Center, End, Stretch` | Acts in the same way as **PrimaryAxisAlignment**, but on the opposite *Orientation*. Only affects an item. |
| PrimaryLength        | `<value>`                     | Sets the width OR the height of one of the items inside the Auto Layout. Depends on the **Orientation**. If the Orientation is horizontal, it will set the **Width**. if it is Vertical, is will set the **Height** . |
| CounterLength        | `<value>`                     | Sets the width OR the height of one of the items inside the Auto Layout. Depends on the **Orientation**. If the Orientation is horizontal, it will set the **Height**. if it is Vertical, is will set the **Width** . |


> [!TIP]
> It is possible to resize the plugin by dragging the lower right corner of its window. Simply hover the corner and drag it when the cursor changes for a double *resize* arrow.


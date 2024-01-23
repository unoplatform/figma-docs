---
uid: Uno.Figma.Learn.Developers.Plugin
---

# Guide to Using Uno Platform Figma Toolkit (UFPMT) and Plugin

## Essential Links

Before diving into the Uno Platform Figma Toolkit, ensure you have the Uno Platform Plugin installed. The installation guide is available on the [download page](../../download.md).

## Overview of Uno Platform Figma Toolkit (UFPMT) and Plugin

Uno Platform Figma Toolkit (UFPMT) and Uno Plugin are essential tools that facilitate the transition from high-fidelity designs to development, specifically by generating XAML code from Figma designs.

UFPMT comes loaded with components, text styles, and color styles, all of which are automatically recognized by the plugin and directly converted to XAML. This enables designers to preview the look, behavior, and corresponding code of their designs in real-time.

The functionalities of the Uno Plugin are organized into six main tabs: [Properties](properties-tab.md), [Preview](preview-tab.md), [Export](export-tab.md), [DataContext](datacontext-tab.md), and [Settings](settings-tab.md).

## General Plugin Guidelines

- **Layer Selection**: For most features to function, at least one layer in the document needs to be selected.
- **Starting Point**: To leverage the full potential of the plugin, start by duplicating UFPMT. Skipping this step may limit the plugin's capability to recognize its native components and styles.
- **Refreshing Views**: Depending on your settings, refreshing the plugin might be necessary to see updates.
- **Properties Tab**: Assign behaviors and bindings to components.
- **Preview Tab**: Visualize the generated XAML.
- **Export Tab**: Export generated code including themes and localization files.
- **DataContext Tab**: Set mock data for bindings, which can be previewed in the Preview tab.

> [!NOTE]
> Generating XAML and its preview can be resource-intensive and may take some time.

## Understanding Auto Layouts

The foundation of the Uno Plugin's functionality lies in the **Auto Layout** feature from Figma. For components to be displayed as intended and benefit from auto-resizing features, they should be placed within an **Auto Layout**.

- **Binding**: By default, data set with the **Content** field in the **Properties** tab will be applied to the *DataContext* property of the Auto Layout.

| Property             | Options                       | Description                                                  |
| -------------------- | ----------------------------- | ------------------------------------------------------------ |
| Orientation          | `Horizontal, Vertical`        | Defines how components in the Auto Layout will be arranged.  |
| Spacing              | `<value>`                     | Sets the distance between items.                             |
| Justify              | `Stack, SpaceBetween`         | Determines the distribution of items within the layout.      |
| PrimaryAxisAlignment | `Start, Center, End, Stretch` | Aligns items based on the selected orientation.              |
| PrimaryAlignment     | `Auto, Stretch`               | Controls how much space an item occupies.                    |
| CounterAlignment     | `Start, Center, End, Stretch` | Adjusts item alignment opposite to the primary axis.         |
| PrimaryLength        | `<value>`                     | Sets the width or height of items, depending on orientation. |
| CounterLength        | `<value>`                     | Sets the secondary dimension of items.                       |

> [!TIP]
> You can resize the plugin window by dragging its lower right corner, when the plugin is used in Figma Designer mode.

This comprehensive guide provides a roadmap for developers to effectively utilize the Uno Platform Figma Toolkit and Plugin, ensuring a smooth and efficient design-to-development workflow.

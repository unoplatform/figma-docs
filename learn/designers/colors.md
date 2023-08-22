---
uid: Uno.Figma.Learn.Designers.Colors
---

# Colors

## How to Use Color Styles

### Introduction

Toolkit comes preloaded with a set of semantic color styles allowing project-specific colors to easily be applied to all components of the design system and their states. Each semantic color style has a predefined role to play, it can be customized by changing its HEX values E.G.: a *Filled* Button uses PrimaryColor as its fill color, while *Elevated* and *Tonal* Buttons use PrimaryColor to fill only their labels. So changing the HEX value of PrimaryColor would impact these buttons (as well as almost every component in the design system). This can easily be tested and experimented with from the *Getting Started* page of the Toolkit.

![](assets/colors1.png)

> [!CAUTION]
> Colors applied outside the provided color styles will not be in XAML generated via the plugin.

## How to Apply Colors Globally

### Steps

1. **Make sure there is nothing selected**. Using the *Color Styles* panel on the right side of the screen, expand the color drawer.
2. **Right-click on the color and choose edit style**. Or simply hover and click the appearing icon.

   ![](assets/color-edit.png)

3. From the *Properties* section choose the HEX code of the desired color. Close all open panels, by clicking the ✕ icon. You should now see your color updating throughout the document.

   ![](assets/color-edit-properties.png)

> [!TIP]
> It is recommended to do this as the first step of setting up the document. But it can be changed at any time in the future.

> [!CAUTION]
> Changing the color when there's something selected in Figma will only affect the selection itself, not the entire document, and the changes won't be exported in XAML.  

## How to apply Color to components

1. Select the component from the *Layers* panel in Figma and expand it;
2. Select the layer named `◇ Template/.Templst_[component name]*`;
3. Select the color to change in the *Color Selection* panel on the right-hand side of your monitor;
4. Right-click on the color and choose *Edit Style*;
5. From the Properties section choose the HEX code of the desired color. Close all open panels, by clicking the X.

   ![](assets/colors-apply.png)

*The top layer of a component cannot be colored.*

## How to Change Colors of Component States

Changing HEX values for states of a component is not currently supported through the plugin. In the Figma file most component states are filled using color styles suffixed with the word *brush*. After editing the main colors in the file, the associated brushes used to denote states need to be edited manually to show the updated values to your DEV team. 

>[Note!] The plugin only generates code for color styles suffixed with the word *Color*, *brush* suffixed styles are not generated. HEX value changes to states must be handled by your DEV team.

### Steps:

1. Select the component from the *Layers* panel in Figma and expand it
2. Update colors to both: `State Layer` AND `◇ Template/.Templst_[component name]`

   ![](assets/colors-update.png)

## Custom Colors

Custom Colors allow you to add more colors to the already available palette and use it consistently across your designs. In this guide, you will learn how to create custom colors in Figma, apply them to your UI elements, and export them. For step-by-step instructions, please refer to the detailed documentation page.

The quick guide to using custom colors [for designers](/doc-public/learn/designers/Custom%20Colors).

To access the detailed documentation page, [click here.](../developers/custom-colors.md)

# Colors

## How to Use Colors

### Introduction

Toolkit comes preloaded with a set of semantic colors allowing project-specific colors to easily be applied to all components of the design system and their states. Each semantic color style has a predefined role to play, it can be customized by changing its HEX values, but it's not possible to change its roles in the design system without creating custom code to support that use case. E.G.: a *Filled* Button uses PrimaryColor as its fill color, while *Elevated* and *Tonal* Buttons use PrimaryColor to fill only their labels. So changing the HEX value of PrimaryColor would impact these buttons (as well as almost every component in the design system). This can easily be tested and experimented with from the *Getting Started* page of the Toolkit.

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
> Changing the color when there's something selected in Figma will only affect the selection itself, not the entire document and the changes won't be exported in XAML.

## How to apply Color to components

1. Select the component from the *Layers* panel in Figma and expand it;
2. Select the layer named `◇ Template/.Templst_[component name]*`;
3. Select the color to change in the *Color Selection* panel on the right-hand side of your monitor;
4. Right-click on the color and choose *Edit Style*;
5. From the Properties section choose the HEX code of the desired color. Close all open panels, by clicking the X.
   ![](assets/colors-apply.png)

** The top layer of a component cannot be colored.*


## How to Change Colors of Component States

Component visual states are usually defined as an extra layer of their main color with varying degrees of opacity, changing the main color will impact all states for all component e.g. changing PrimaryColor would change all state colors for types of Buttons. It is not recommended to customize component states individually as the plugin may not generate proper XAML for this.

### Steps:

1. Select the component from the *Layers* panel in Figma and expand it
2. Update colors to both: `State Layer` AND `◇ Template/.Templst_[component name]`
   ![](assets/colors-update.png)

## Custom Colors

Custom Colors allow you to add more colors to the already available palette and use it consistently across your designs. In this guide, you will learn how to create custom colors in Figma, apply them to your UI elements, and export them. For step-by-step instructions, please refer to the detailed documentation page.

To access the detailed documentation page, [click here.](../developers/custom-colors.md)

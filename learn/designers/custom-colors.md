---
uid: Uno.Figma.Learn.Designers.CustomColors
---

# Using Custom Colors

## What are Custom Color Styles, and Why Use Them?

Custom colors allow you to add Color Styles to those already provided by the Uno Figma Material Toolkit. This added functionality can be used to:

* Add new color styles to both the Light and Dark themes;
* Create a "fixed" color style for your design that displays the same HEX value in both Light and Dark themes.

You may want to do this in your app to denote statuses, add color tags, introduce more accent colors, or even support custom vector illustrations. While we encourage you to stick to the color roles provided by the Material design system, we understand that sometimes primary, secondary, and tertiary accent colors aren't enough to cover all use cases. That's why we introduced Custom Color Styles.

> [!NOTE]
> Adding a new color style will not generate any associated styles automatically. For example, adding a new custom style named "AwayStatusColor" would not automatically generate a Dark theme equivalent, nor generate "OnAwayStatusColor", "AwayStatusColorContainer", "OnAwayStatusColorContainer", which your project may or may not need.

![Adding Custom Color Styles](assets/CustomColorStyle.png)

## How to Add a Custom Color Style

1) From the [Uno Figma Toolkit file](https://aka.platform.uno/uno-figma-material-toolkit), make sure you have nothing selected.
2) Go to the *Design* panel on the right side of the screen, find the *Color Style* section, and hover over the "Light" theme.
3) Click the ➕ icon to add a custom color style to the Light theme.
4) Name your color, pick a value, and click Create Style.
5) Optional: If you want your new style to have a Dark theme counterpart, repeat the above steps but select the "Dark" theme in step 2, and use the same name for both custom styles.

> [!IMPORTANT]
> Custom color names **MUST END WITH `Color`**.

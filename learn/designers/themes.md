---
uid: Uno.Figma.Learn.Designers.Themes
---

# Color Themes

## Generating Color Themes with Uno Toolkit

To enhance the aesthetic appeal and consistency of your project, the Uno Toolkit offers customizable Light and Dark themes. These can be tailored to meet the specific color requirements of your project. For additional customization or to develop a unique color scheme, the **Material Theme Builder** is an invaluable tool.

To dynamically switch color themes in your Figma document, the **Atlas Theme Manager Plugin** is recommended. More details about these tools are available on the [Download & Tools](../../download.md) page.

## Creating a Custom Theme Package

The Uno Figma Plugin supports importing theme packages, allowing for extensive customization of your Figma file. Utilize the **Material Theme Builder** to craft a personalized theme, which can then be imported into Figma.

### Steps to Generate a Theme Package

1. Access the **Material Theme Builder Tool** online.
2. Customize your theme to fit your project's needs, including the creation of custom colors.
3. In the **Export** section, be sure to select the **Material Tokens (DSP)** option to download your package as a zip file. This step is crucial, as the Uno Plugin requires this specific format for successful import.

> [!CAUTION]
> The Material Theme Builder does not currently support re-importing your theme package. To modify your theme, you will need to either start from scratch or maintain the Theme Builder web page for reference.

## Importing a Theme Package into Figma

### Steps for Import

1. In Figma, open your file and select the **Uno Plugin** from the Plugins menu.
2. Within the Uno Plugin, navigate to the **Properties Tab** and locate the **Theme Package** section.
3. Click on **Import**, then choose the zip file you downloaded from the Material Theme Builder. It's essential to use the unaltered zip file for a smooth import process.
4. Confirm to apply the theme to your Figma file.

> [!TIP]
> If the imported theme doesn't align with your expectations, use Figma's **Undo** feature to revert all changes at once.

> [!TIP]
> The Uno Plugin will only process relevant files within the theme package, disregarding any unrelated content and notifying you of such instances.

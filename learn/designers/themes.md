---
uid: Uno.Figma.Learn.Designers.Themes
---

# Color Themes

## Generating Color Themes with Uno Toolkit

To enhance the aesthetic appeal and consistency of your project, the Uno Toolkit offers customizable Light and Dark themes. These can be tailored to meet the specific color requirements of your project. For additional customization or to develop a unique color scheme, the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder) is an invaluable tool.

To dynamically switch color themes in your Figma document, the **Atlas Theme Manager Plugin** is recommended. More details about these tools are available on the [Download & Tools](../../download.md) page.

## Creating a Custom Theme File

The Uno Figma Plugin supports importing theme files, allowing for extensive customization of your Figma file. Utilize the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder) to craft a personalized theme, which can then be imported into Figma.

### Steps to Generate a Theme File

1. Access the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder) online.
2. Customize your theme to fit your project's needs, including the creation of custom colors.
3. In the **Export** section, be sure to select the **Material Theme (JSON)** option to download your theme as a JSON file. This step is crucial, as the Uno Plugin requires this specific format for successful import.

> [!CAUTION]
> The Material Theme Builder does not currently support re-importing your theme file. To modify your theme, you will need to either start from scratch or maintain the Theme Builder web page for reference.

## Importing a Theme File into Figma

### Steps for Import

1. In Figma, open your file and select the **Uno Plugin** from the Plugins menu.
2. Within the Uno Plugin, navigate to the **Properties Tab** and locate the **Theme File** section.
3. Click on **Import**, then choose the JSON file you downloaded from the Material Theme Builder.
4. Confirm to apply the theme to your Figma file.

> [!TIP]
> If the imported theme doesn't align with your expectations, use Figma's **Undo** feature to revert all changes at once.

> [!TIP]
> The Uno Plugin will only process relevant files within the theme file, disregarding any unrelated content and notifying you of such instances.

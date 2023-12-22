---
uid: Uno.Figma.Learn.Designers.Dsp
---

# Importing a DSP Color Theme

Supports DSP files from the web version of the Material Theme Builder.

## What is DSP, and Why Use It?

Design System Package (DSP) is an "*open-format folder-structure created to help teams share design system information across tools.*"

The Uno plugin for Figma allows you to import a DSP file generated from the online version of the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder). This provides a shortcut to exploring and applying different color themes for your app design. Once imported into the Uno Figma Toolkit, all its components will update to follow your new color theme, saving you time and effort.
The Uno plugin for Figma allows you to import a DSP file generated from the online version of the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder) . This gives you a shortcut to exploring and applying different color themes for your app design. Once imported into the Uno Figma Toolkit all of it's components will update to follow your new color theme saving you time and effort.

We recommend doing this at the start of the design phase, but you can apply a new theme to your design at any point in the design cycle.

![Before DSP Import](assets/before-dsp-import.png)



> [!IMPORTANT]
> Due to Figma restrictions, we can't import a DSP file in Figma Developer Mode. The feature will only be available when the plugin is runnning in Design Mode.


## How to Import the DSP File

1) Generate your color theme from the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder).
2) Click the *Export* button in the top right area of the website and make sure to select **Material Tokens (DSP)** from the dropdown menu.
3) From the [Uno Figma Toolkit file](https://aka.platform.uno/uno-figma-material-toolkit), select a page from your design and launch the [Uno Figma plugin](https://aka.platform.uno/uno-figma-plugin).
4) Go to the *Properties* Tab, select *Application*, and click *Import DSP Theme*.
5) From the file picker window, navigate to the location of the *material-theme.zip* file you exported in step 2 (no need to unzip the file).

1) Generate your color theme from the [Material Theme Builder](https://aka.platform.uno/uno-material-themebuilder);
2) Click the *Export* button in the top right area of the website and make sure to select **Material Tokens (DSP)** from the drop down menu;
3) From the [Uno Figma Toolkit file](https://aka.platform.uno/uno-figma-material-toolkit) select a page from your design and launch the [Uno Figma plugin](https://aka.platform.uno/uno-figma-plugin);
4) Go to the *Poperties* Tab then select *Application* and click *Import DSP Theme*;
5) From the file picker window navigate to the location of the *material-theme.zip* file you exported in step 2 (no need to unzip the file).

> [!IMPORTANT]
> Brushes will not be automatically updated when importing a DSP file. Make sure to update the brushes in Figma to match the new colors they are based on.

## After DSP Import
![After DSP Import](assets/after-dsp-import.png)

# Export Tab

## Using the Export Tab

The Export tab is another powerful tool to inspect generated code and export to developers.

The left-top dropdown allows you to alternate among `Xaml`, `Colors Override File`, `Fonts Override File` and `Localization File`. Contextual controls at the bottom of the tab allow you to: set view type, refresh view and export the code;

Exporting process is done by adding the tab content to the clipboard, so you can paste it into your favorite text editor.

> [!NOTE]
> Proper generation depends on usage of the proper templates and components, please read the [New design guidelines](../designers/starting-new-design.md) before starting a new project;

### Steps to Use Export Tab

1. Select the page or component to inspect;
2. From Figma's *Plugins* menu select *Uno Platform*;
3. Click the *Export* tab (third one from the left);
4. Click the *Refresh* button at the bottom of the tab.

### Export Options

The plugin is able to export both Xaml and C# code. You can easily select which option you want to generate using a dropdown field.
At left-top dropdown, you can choose what to export.

It is possible to export the full screen code, resources like colors, fonts, localization, user controls, among other options, depending on your selected design.

> [!NOTE]
> To override your application's resources, simply copy the text there into your Override file, as documented in the [Uno Themes documentation](https://platform.uno/docs/articles/external/uno.themes/doc/material-getting-started.html#customize-color-palette).

![](assets/export.png)

> [!WARNING]
>
> This features will only work if the document has been created by duplicating the [Uno Toolkit](../designers/starting-new-design.md) document.
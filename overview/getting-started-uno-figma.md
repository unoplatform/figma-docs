---
uid: Uno.Figma.Overview.GettingStarted
---

# Design and Build Uno Platform Applications With Figma

It is now possible to use Figma to design and build Uno Platform applications. Designers can use the highly collaborative Figma environment to fine-tune the User Experience (UX) while putting in place building blocks of an application following the Material Design language.
Using the [Uno Platform Figma Plugin](../download.md), it is possible to visualize how the application will render and to export actual XAML for use in Visual Studio for the application. This application is also ready for localization, ready for accessibility, and can optionally make use of [Uno Extensions](https://aka.platform.uno/uno-extensions) (Reactive, Navigation...).
Using the [Uno Platform Figma Plugin](../download.md), it is possible to visualize how the application will render and export actual XAML to use in Visual Studio for the application. This application is also ready for localization, ready for accessibility and can optionally use of [Uno Extensions](https://aka.platform.uno/uno-extensions) (Reactive, Navigation...).

## Designer's Side

### Quick Start

1. Duplicate the [Uno Platform Material Toolkit](https://aka.platform.uno/uno-figma-material-toolkit).
2. Open the document and go to the _Getting Started_ page. There's a lot of information there to adjust the colors, the typography, and how to start a new project.
3. Open the _Theme_ page and **ensure that nothing is selected** in the document. On the right-hand side of Figma, there's the **Color Styles** section where it is possible to adjust colors for the styles of the application. When hovering the mouse over a specific color, an _Edit Style_ button appears. This button allows for picking another color for the chosen style.
4. Open the _Example App_ page. You can rename it to fit your application name or even create new ones as needed.
5. Creating a new page: Open the _Assets_ pane (at the top/left of the screen) and select `Templates`. Open the `Templates / Page Templates` section. Pick one of the templates and drag it onto the design surface.
2. Open the document and go to the _Getting started_ page. There's a lot of information there to adjust the colors, the typography, and how to start a new project.
3. Open the _Theme_ page and **ensure that nothing is selected** in the document. On the right-hand side of Figma, there's the **Color Styles** section where it is possible to adjust colors for the styles of the application. When passing the mouse over a specific color, there's an _Edit style_ button that appears. This button allows for picking another color for the chosen style.
4. Open the _Example app_ page. You can rename it to fit your application name or even create new ones as needed.
5. Creating a new page: Open the _Assets_ pane (at the top/left of the screen) and select `Templates` open the `Templates / Page templates` section. Pick one of the templates and drag it on the design surface.
6. Adding components to an existing page: Open the _Assets_ page (at the top/left of the screen) and open the `Components` section. Pick a desired component and drag it inside an existing page on the design surface.

### Tips for Designers

* Time should be taken to ensure the _Resizing_ section is set to appropriate values for each component. This is important to ensure the proper layout of the result.

Next: [Build a Simple Login Page with the Uno Figma Plugin](../learn/designers/simple-login-page.md)

## Developer's Side

1. The [Uno Platform Figma Plugin](../download.md) must be installed for the current user.
2. Open the document saved by the designer. Since a plugin will be used, **Edit privileges are required** by Figma to run any plugin on a document.
3. Open the _Example App_ page (it may be renamed to something else by the designer) and right-click on a designed screen.
4. Open the `Plugins`-> `Uno Platform`. The initialization could take a few seconds.
5. Pick the second tab (the "PLAY ICON") called `Preview`.
6. Click the Refresh button at the bottom of the plugin.
7. After a few seconds, a XAML-rendered version of the selected page should be displayed.
8. Pick the third tab called `Export`. An editor will display the generated code. Using the dropdown on the left, it is possible to alternate among code for the `Root Screen`, `Colors and Font Overrides Files`, `Localization File`, `Custom Component`, and more!
9. It is also possible to choose between `XAML` and `C# Markup` formats. See [Export Tab](../learn/developers/export-tab.md) for more details.
7. After few seconds, a XAML rendered version of the selected page should be displayed.
8. Pick the third tab called `Export`. An editor will display the generated code. Using the dropdown on the left, is possible to alternate among code for the `Root Screen`, `Colors and Font Overrides Files`,  `Localization File`, `Custom Component` and more!
9. It is also possible to choose betwee `Xaml` and `C# Markup` formats. See [Export Tab](../learn/developers/export-tab.md) for more details
10. An `Export` button at the bottom right of the plugin will copy the content into the clipboard, which can be used to send the code to the IDE of preference.

### Tips for Developers
* It is possible to change namespaces in the first tab called `Properties`. By default, an Application Namespace will be created from the document's name. It is also possible to define sub namespaces for Style and View Layer. The same namespace collection is used for the entire Figma document.

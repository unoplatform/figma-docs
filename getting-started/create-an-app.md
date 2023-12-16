---
uid: Uno.Figma.GettingStarted.CreateAnApp
---

# Create an app

This section will guide you through the process of creating a new app using the Uno Platform Figma Plugin and the _Example App_ present by default in the [Uno Platform Material Toolkit](https://aka.platform.uno/uno-figma-material-toolkit) file, using the [Uno Platform Figma Plugin](https://aka.platform.uno/uno-figma-plugin).

> [!IMPORTANT]
> Is it required to have completed the [Setup](xref:Uno.Figma.GettingStarted.Setup) section before starting this one.

## Create a project using Visual Studio

For this project, we will be using the unoapp solution template. This template includes two preset configurations, blank and recommended, and a large number of other options that can be used to define the structure of the app to be created by the template.

For this project, we're going to select the blank preset, which only includes the minimum features required for an Uno Platform application. We're also going to select the Material theme and include the Uno Toolkit for the helper functions to switch themes.

By default, the project will be created using the XAML UI language.

Run the following command in a terminal to create a new project:
```shell
dotnet new unoapp -preset blank -toolkit true -theme material -theme-service -o MyFirstAppFromFigma
```

### Step 1 - Open the solution, compile and run it
1. Open the generated `MyFirstAppFromFigma.sln` solution in your favorite IDE (following screenshots will use Visual Studio)
2. In the top toolbar, select the platform you like as your startup project (following screenshots will use `MyFirstAppFromFigma.Windows`)
3. Press F5 to run the app and ensure it builds correctly
4. Locate the page `MainPage.xaml` in the `MyFirstAppFromFigma` library project
3. Compile the project to ensure it builds correctly
3. Switch to Figma (next section)

### Step 2 - Make Figma generates the right XAML
1. Go back to Figma, in the document you created in the [Design to Code](xref:Uno.Figma.GettingStarted.DesignToCode) section.
2. Open the plugin (more details in the [Setup](xref:Uno.Figma.GettingStarted.Setup) section)
3. In Figma, select the _01. Login_ frame
4. In the plugin, navigate to the _Properties_ tab
5. In the _Page Name_ field, write `MainPage`
6. Navigate to the _Application_ subtab
7. In the _Application Name_ field, write `MyFirstAppFromFigma`
8. Go back to the _Export_ tab
9. Click on the _Refresh_ button
10. Now click on the _Copy_ button to copy the generated XAML to the clipboard

### Step 3 - Paste the generated XAML into app project
1. Go back to your IDE (Visual Studio in this example)
2. Replace the content of the `MainPage.xaml` file with the generated XAML, from the clipboard
3. Press F5 to run the app

## What you just did

You just created a new app, using Uno Platform and generated XAML from a Figma document.

## Next steps

This tutorial has shown you how to create a new app using the Uno Platform Figma Plugin and the _Example App_ present in the _Uno Material Toolkit_ Figma document.

Use this documentation to understand how to use the plugin to generate code from your own Figma document.

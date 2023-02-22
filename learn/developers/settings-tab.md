# Settings Tab

This tab allows to change various settings for the Plugin.

## Versioning

At the top of the settings tab, you can see various versioning:

* *Uno Figma Plugin*: That's the version of the plugin itself;
* *Uno.UI*: The version of `Uno.UI` currently used by the plugin;
* *Uno.Themes*: The version of `Uno.Themes` used;
* *Uno.Toolkit.UI*: The version of the Toolkit currently used;
* *Uno.Extensions*: The version of `Uno.Extensions` used.

## Settings

* Preview

  * *Auto Sync*: when set, preview tab is updated each time a new selection is done in Figma.

    > [!CAUTION]
    > Using this feature is resource expensive.

* General

  * *Bindings*: Defines if the generation of _bindings_ should be in generated XAML;
  * *Localization*: Defines is the generation of `x:Uid` should be in generated XAML;
  * *Accessibility*: Defines if _AutomationPeer_ properties should be in generated XAML;
  * *Layout optimizer*: Define if the Layout optimizer should be use

  > [!CAUTION]
    > The layout optimizer is still in the experimental phase.

  > [!NOTE]
  > Options here, except _Bindings_, won't change the XAML generated in the preview, and will only be present in the exported version.

* Extensions

  * *Reactive*: Defines if `<FeedView />` controls should be in generated XAML;
  * *Navigation*: Defines if *Uno Navigation Extensions* instructions should be in generated XAML.

* Styling: This is advanced and should not be changed.

* Settings

  * *Development*: Used by Uno developers to diagnose problems. Not useful unless instructed by support to use it;
  * *Plugin Theme*: Triggers dark/light mode for the plugin interface;
  * *Share usage analytics*: Opt in/out of the usage analytics to help Uno improving the plugin by gathering anonymous usage data of the plugin.

## Settings for Generated XAML

Not all settings will have effect on generated XAML in the same way...

|       Setting | Effect in Preview | Effect on Export |
| ------------ | ----------------- | ---------------- |
|    `Bindings` | settings          | settings         |
| `Localization` | false             | settings         |
| `Accessibility` | false             | settings         |
|    `Reactive` | false             | settings         |
|  `Navigation` | false             | settings         |


## Steps to use Settings tab

1. From Figma's *Plugins* menu select *Uno Platform*;

2. Click the *Settings* tab (last tab);
3. Make changes;
4. Changes are automatically saved.
# Settings Tab

This tab allows to change various settings for the Plugin.

> [!CAUTION]
>
> Don't forget to save your settings!

## Versioning

At the top of the settings tab, you can see various versioning:

* *Uno Figma Plugin*: That's the version of the plugin itself;
* *Uno.UI*: The version of `Uno.UI` currently used by the plugin;
* *Uno.Toolkit.UI*: The version of the Toolkit currently used. This also define the version of *Uno Themes*;
* *Uno.Extensions*: The version of Uno.Extensions used.

## Settings

* Preview

  * *Auto Sync*: when set, preview tab is updated each time a new selection is done in Figma.

    > [!CAUTION]
    >
    > Using this feature is resource expensive.

* General

  * *Bindings*: Defines if the generation of _bindings_ should be in generated XAML;
  * *Localization*: Defines is the generation of `x:Uid` should be in generated XAML;
  * *Accessibility*: Defines if _AutomationPeer_ properties should be in generated XAML.

* Extensions

  * *Reactive*: Defines if `<FeedView />` controls should be in generated XAML;
  * *Navigation*: Defines if *Uno Navigation Extensions* instructions should be in generated XAML;

* Styling: This is advanced and should not be changed.

* Settings

  * *Save Properties as Shared*: Defines if properties set to elements in Figma should be private or shared with othe plugins;
  * *Development*: Use by Uno developers to diagnose problems. Not useful unless instructed by support to use it;
  * *Dark mode*: Trigger dark/light mode for the plugin interface;
  * *Share usage analytics*: Opt in/out of the usage analytics to help Uno improving the plugin by gathering anonymous usage data of the plugin.


## Steps to use Data Context tab

1. From the *Plugins* menu select *Uno Platform*;

2. Click the *Settings* tab (sixth one from the left);
3. Make changes;
4. Click the *Save button* at the bottom of the tab.
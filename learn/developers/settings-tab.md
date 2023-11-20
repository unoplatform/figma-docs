---
uid: Uno.Figma.Learn.Developers.Tabs.Settings
---

# Settings Tab in Uno Figma Plugin

## Overview

The Settings tab in the Uno Figma Plugin offers various adjustable parameters to customize the plugin's functionality and behavior.

### Version Information

At the top of the Settings tab, you can find version details of different components used by the plugin:

- **Uno Figma Plugin**: Version of the plugin itself.
- **Uno.UI**: Version of `Uno.UI` utilized by the plugin.
- **Uno.Themes**: Version of `Uno.Themes` in use.
- **Uno.Toolkit.UI**: Version of the Toolkit being used.
- **Uno.Extensions**: Version of `Uno.Extensions` employed.

### Configurable Settings

#### Preview Settings

- **Auto Sync**: Automatically updates the Preview tab when a new selection is made in Figma. 
  > [!CAUTION]
  > This feature is resource-intensive.
- **Extract Image**: Extract images from Figma to show in the preview. When disabled it will generate placeholders. Images are not in exported XAML. 

#### General Settings

- **Bindings**: Toggles the generation of bindings in the exported XAML.
- **Localization**: Determines the inclusion of `x:Uid` in the exported XAML.
- **Accessibility**: Decides whether _AutomationPeer_ properties appear in the exported XAML.
- **Layout Optimizer**: Activates the layout optimizer.

  > [!NOTE]
  > Except for _Bindings_, these settings do not affect the preview-generated XAML but are applied in the exported version.

#### Extensions Settings

- **Reactive**: Controls the inclusion of `<FeedView />` controls in the generated XAML.
- **Navigation**: Toggles the inclusion of Uno Navigation Extensions instructions in the generated XAML.

#### Styling Settings

- Advanced settings for styling that are generally not modified.

#### Plugin Settings

- **Plugin Theme**: Switches between dark and light modes for the plugin interface.
- **Share Usage Analytics**: Opt in or out of usage analytics to aid Uno in improving the plugin through anonymous data collection.

### Impact of Settings on XAML Generation

|       Setting | Effect in Preview | Effect on Export |
| ------------: | :---------------: | :--------------: |
|    `Bindings` |      Settings     |      Settings    |
| `Localization`|       False       |      Settings    |
| `Accessibility`|      False       |      Settings    |
|    `Reactive` |       False       |      Settings    |
|  `Navigation` |       False       |      Settings    |

### Utilizing the Settings Tab

1. Access the Uno Platform Plugin from Figma's *Plugins* menu.
2. Open the *Settings* tab, located as the last tab.
3. Adjust settings as needed.
4. Changes are saved automatically, streamlining the configuration process.

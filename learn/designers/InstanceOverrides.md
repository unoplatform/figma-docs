# How to Use Instance Overrides

## Overview

Uno Figma Platform Material Toolkit (UFPMT) includes a set of components designed and styled to closely follow [Material 3 color guidelines](https://m3.material.io/styles/color/the-color-system/color-roles). Designers using UFPMT should be intimatly familiar with the Material color system before attempting to substitute color roles through out components or they run the risk of finding nasty surprises in the XAML generated from their compositions come integration time. At least that was the case before UFPMT introduced its new *Instance* *Overrides* feature. While we still recommend you get familiar with Material color management, overrides gives you more control and flexibility in the areas of: swapping color roles and managing component borders (strokes in figma parlance).

 ## How it works

Instance overrides works by detecting changes between a component's Editable Template and it's instances used in your Figma design file. This is done when you use the Uno Figma Plugin to generate XAML or a Preview of a selected composition. If your design uses a consistant set of buttons yet you need to create a new style for a certain use case, like a red destructive change confirmation button, the plugin will now detect the overrides you applyed to button instances and generate the proper XAML to reflect this new button style.

![](images/overriden-button-style.png)

## Instance overrides per component

Foreground color usually referers to content (in Material guidelines) of a component like text and icons as well as state overlays. Background color is usually the fill color used to define the shape of the component. Border is a synonyme for stroke (in Figma) and Outline (in Material) and is a line defining the outer border of a component.

### [Button](../../components/button.md)
| Property         | Currently supported instance overrides                       | Edit this layer in Figma  |
| ---------------- | ------------------------------------------------------------ | ------------------------- |
| Background color | Swap Primary and Surface fill colors with other color roles from the toolkit. | State Layer               |
| Foreground color | Swap any colors roles assigned to button labels and icons with other color roles from the toolkit. | Label, Vector             |
| Border           | Swap button border (aka Stroke) colors with other color roles from the toolkit. Add, remove and edit border thickness from instances. | Template/.Template_Button |


### [Floating Action Button (FAB)](../../components/fab.md)

| Property                     | Currently supported instance overrides                       | Edit this layer in Figma  |
| ---------------------------- | ------------------------------------------------------------ | ------------------------- |
| Background color             | Swap PrimaryContainer fill color with other color roles from the toolkit. | Template/.Template_FAB    |
| Foreground color             | Swap any colors roles assigned to FAB labels and icons with other color roles from the toolkit. | Label, Vector             |
| Border                       | Swap FAB border (aka Stroke) colors with other color roles from the toolkit. Add, remove and edit border thickness from instances. | Template/.Template_Button |

### [Icon Button](../../components/icon-button.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma        |
| ---------------- | ------------------------------------------------------------ | ------------------------------- |
| Background color | Not applicable                                               | n/a                             |
| Foreground color | Swap any colors roles assigned to ToggleButton icons with other color roles from the toolkit. | Vector (checked and unchecked)* |

### [Icon Toggle Button](../../components/icon-toggle-button.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma        |
| ---------------- | ------------------------------------------------------------ | ------------------------------- |
| Background color | Not applicable                                               | n/a                             |
| Foreground color | Swap any colors roles assigned to ToggleButton icons with other color roles from the toolkit. | Vector (checked and unchecked)* |

### [Radio Button](../../components/radio-button.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Swap RadioButton Primary color role with other color roles from the toolkit. | Icon, Color              |
| Foreground color | Swap OnSurface color role used for text label with other color roles from the toolkit. | Content                  |
| Border           | Add, remove and edit border thickness from instances. Use any color role from the Toolkit. | RadioButton              |

### [Combo Box](../../components/combo-box.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Swap ComboBox Surface color role with other color roles from the toolkit. | Input                    |
| Foreground color | Swap OnSurface color role used for text and icons with other color roles from the toolkit. | Text, Vector             |
| Border           | Swap ComboBox border (aka Stroke) colors with other color roles from the toolkit. Add, remove and edit border thickness from instances. | Input                    |

### [Divider](../../components/divider.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma   |
| ---------------- | ------------------------------------------------------------ | -------------------------- |
| Foreground color | Swap fill color role used for dividers with any other color roles from the toolkit. | Template/.Template_Divider |

### [Hyperlink](../../components/hyperlink-button.md)

| Property         | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Add a fill color with color color roles from the toolkit.    | Hyperlink Button         |
| Foreground color | Swap Primary or OnSurface color role used for hyperlinks with any other color roles from the toolkit. | Link                     |
| Border           | Add, remove and edit border thickness from instances. You can assign any toolkit color to the border property. | Hyperlink Button         |

### [Password Box](../../components/password-box.md)

| Property      | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Swap fill color role with any other color roles from the toolkit. | Input                    |
| Foreground color | Swap color roles used for text and icons with any other color roles from the toolkit. | Text, Vector             |
| Border           | Add, remove and edit border thickness from instances. Use any color role from the Toolkit. | Input                    |

### [Slider](../../components/slider.md)

| Property           | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Swap Slider Primary color role with other color roles from the toolkit. | Inactive track           |
| Foreground color | Swap OnSurface color role used for text label with other color roles from the toolkit. | Color                   |
| Border           | Add, remove and edit border thickness from instances. Use any color role from the Toolkit. | RadioButton              |

### [Text Box](../../components/text-box.md)

| Property          | Currently supported instance overrides                       | Edit this layer in Figma |
| ---------------- | ------------------------------------------------------------ | ------------------------ |
| Background color | Swap fill color role with any other color roles from the toolkit. | Input                    |
| Foreground color | Swap color roles used for text and icons with any other color roles from the toolkit. | Text, Vector             |
| Border           | Add, remove and edit border thickness from instances. Use any color role from the Toolkit. | Input                    |

## Controls with no support

The following controls are not supporting overrides right now:

* BottomNavigationBar
* Card
* Checkbox
* Chips
* DatePicker
* Dialogs
* Flyouts
* ListItem
* NavigationBar
* Progress Bar
* RatingControl
* SwipeControl
* Tabs
* ToggleSwitch*












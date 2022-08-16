# TextBox

> **Note:** The **TrailingIcon** of the TextBox will always be the "X" icon whether or not it is changed in Figma.

> **Binding:** By default, Data set with the **Content** field in the **Properties** tab in the plugin will be applied to the *Text* property for this component.

![textbox](.\images\textbox.png)

| Property     | Options                                          | Description                                                  |
| ------------ | ------------------------------------------------ | ------------------------------------------------------------ |
| Type         | `Filled, Outlined`                               | Changes the style of the TextBox                             |
| Property     | `Default, Prefix, Suffix`                        | Adds a measurement units on the left (prefix) or the right (suffix) of the text box. Currently, both Prefix and Suffix are not supported |
| State        | `Enabled, Hover, Active, Focus, Error, Disabled` | Alters the current state of the component, although it doesn't affect the plugin |
| LeadingIcon  | `True/False`                                     | Adds an icon before the input                                |
| TrailingIcon | `True/False`                                     | Adds a "Visibilty" icon after the input. This will not affect the plugin |
| Multiline    | `True/False`                                     | Enables or disables the multiline feature for the TextBox    |

### Extra Customization

> To reach the extra customization features you will need to work your way through the hierarchy of the component to find the specified sub-components.  

- **LeadingIcon:** Allows you to change the icon on the left of the **TextBox**. It will only be displayed if the **LeadingIcon** property is set to Icon.
- **Label:** Allows you to change the text of the **TextBox's** placeholder.

### Overridable Properties

- **Background** 
- **BorderBrush** 
- **BorderThickness** 
- **Foreground** 
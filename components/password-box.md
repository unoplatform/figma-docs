---
uid: Uno.Figma.Components.PasswordBox
---

# PasswordBox

> [!NOTE]
> The **TrailingIcon** of the PasswordBox will always be the "Visibility" icon whether or not it is changed in Figma.

**Binding:** By default, Data set with the **Content** field in the **Properties** tab in the plugin will be applied to the *Password* property for this component.

![passwordbox](./images/passwordbox.png)

## Component Properties

| Property     | Options                                          | Description                                                  |
| ------------ | ------------------------------------------------ | ------------------------------------------------------------ |
| Type         | `Filled, Outlined`                               | Changes the style of the control                             |
| Leading      | `True/False`                                     | Adds a leading icon                                         |

## Content Template Properties

| Property     | Options                                          | Description                                                  |
| ------------ | ------------------------------------------------ | ------------------------------------------------------------ |
| Type         | `Filled, Outlined`                               | Changes the style of the TextBox                            |
| State        | `Enabled, Hovered, Focused, Disabled`            | Alters the current state of the component, although it doesn't affect the plugin |
| Multiline    | `True/False`                                     | Enables or disables the multiline feature for the TextBox    |
| Label        | `True/False`                                     | Show or hide Label                                           |
| Populated    | `True/False`                                     | Show or hide input text content                              |
| Leading      | `True/False`                             | Adds an icon on the left of the TextBox input             |
| Label        | `True/False`                             | Show or hide Label                                        |
| Input Text   | `True/False`                             | Show or hide input text content                           |
| Trailing     | `True/False`                             | Swap visibility of a clear icon. Doesn't affect Plugin    |

## Extra Customization

To reach the extra customization features, you will need to work your way through the hierarchy of the component to find the specified sub-components.

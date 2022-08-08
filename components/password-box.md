# PasswordBox

> **Note:** The **TrailingIcon** of the PasswordBox will always be the "Visibility" icon whether or not it is changed in Figma.

> **Binding:** By default, Data set with the **Content** field in the **Properties** tab in the plugin will be applied to the *Password* property for this component.

![passwordbox](./images/passwordbox.png)

| Property | Options            | Description                          |
| -------- | ------------------ | ------------------------------------ |
| Type     | `Filled, Outlined` | Changes the style of the PasswordBox |
| Leading  | `None, Icon`       | Adds an icon before the input        |

### Extra Customization

> To reach the extra customization features you will need to work your way through the hierarchy of the component to find the specified sub-components.  

- **LeadingIcon:** Allows you to change the icon on the left of the **PasswordBox**. It will only be displayed if the **Leading** property is set to Icon.
- **Label:** Allows you to change the text of the **PasswordBox's** placeholder.

### Overridable Properties

- **Background** 
- **Foreground** 
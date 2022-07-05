# Card

> **Note:** The **Card** will always have at least two property enabled between **Header**, **Media** and **Body**



> **Note:** The **PersonPicture** located in the **Header** will by default have the **Type** Icon



![card](./images/card.png)

| Property | Options              | Description                                                  |
| -------- | -------------------- | ------------------------------------------------------------ |
| Type     | `Elevated, Outlined` | Changes the style of the card                                |
| Header   | `True/False`         | Adds a header that includes a **ProfilePicture** and some text at the top of the card |
| Media    | `True/False`         | Adds an **Image** in the middle of the card                  |
| Body     | `True/False`         | Adds some text and **Buttons** at the bottom of the card     |

### Extra Customization

> To reach the extra customization features you will need to work your way through the hierarchy of the component to find the specified sub-components.  

- **ListItem:** Allows you to change the content of the **Header**. It will only be displayed if  the **Header** property is enabled. See **[ListItem](./list-item.md)** for all the possible customizations.
- **Image:** Allows you to change the image present in the **Media** section. It will only be displayed if  the **Media** property is enabled. See **[Image](./image.md)** for all the possible customizations.
- **ListItem:** Allows you to change the content of the **Body**. It will only be displayed if  the **Body** property is enabled. See **[ListItem](./list-item.md)** for all the possible customizations.
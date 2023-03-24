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


# Custom Card

If you want a completely different content from the existent Card component, here are the steps:


### Steps to create your own Custom Content Card

Part 1:

1. Create a new frame;
2. Edit its content with the look and feel you want for your Card;
3. Convert it to a component, choose a name for it. **Important:** the name must be diferent from "Card";

Part 2:

1. Add an instance of a Card in the place you desire; 
2. In the "Layers" tree, select its first content node. It is an instance of another component;
3. Go to the "Design" tab and swap this instance to your recent created component;
4. At this moment the Card visual will be changed, showing in its content the component you have created;
5. That's it! Now you can run the plugin to generate the screen you created;

> **Note:** For custom content Cards, Plugin will not be able to detect [Overrides](../learn/designers/overrides.md). Also, some attributes coming from default style - like Corner Radius and "elevated" layout (shadow) - will remain.

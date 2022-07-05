# Image

> **Note:** There are 2 different components named **Image** in the Plugin. The difference is that one of them has the **State** property the other doesn't.

> **Note:** The **Image** that will be displayed in the Plugin will be a placeholder and not the actual image. In the plugin, the visual might take a while to load depending on the current [picsum](https://picsum.photos/) server status. 

> **Tip:** Using the **Image** coming directly from Figma will work the same as the Uno component in the Plugin.

> **Tip:** The size of the **Image** image is based on the frame oif the component and not the image it contains.

> **Binding:** By default, Data set with the **Content** field in the **Properties** tab in the plugin will be applied to the *Source* property for this component.



![image](./images/image.png)

| Property | Options               | Description                                                  |
| -------- | --------------------- | ------------------------------------------------------------ |
| Ratio    | `Portrait, 1:1, 16:9` | changes the **Width** and the ***Height** of the image to fit the specified ratio. |
| State    | `Enabled, Disabled`   | Alters the current state of the component, although it doesn't affect the plugin |


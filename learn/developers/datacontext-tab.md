---
uid: Uno.Figma.Learn.Developers.Tabs.DataContext
---

# DataContext Tab in Uno Figma Plugin

## Using the DataContext Tab

The DataContext tab within the Uno Figma Plugin plays a crucial role in setting the `DataContext` for bindings, especially useful in the [*Preview* tab](preview-tab.md). This feature is key for simulating how data interacts with UI elements in the app.

### Important Considerations

- **Data Format**: The DataContext tab uses JSON format for data input.
- **Saving Data**: Changes must be saved to take effect.
- **Developer Collaboration**: It is recommended that the JSON content be provided by a developer to ensure it matches the structure of the ViewModels that will be used during app development. This content may need updates if the ViewModels change.

## Implementing DataContext

1. **Select a Page or Component**: In Figma, choose the item you wish to edit.
2. **Open Uno Platform Plugin**: From Figma's Plugins menu, select Uno Platform.
3. **Access DataContext Tab**: Click on the DataContext tab, which is the fourth icon from the left in the Uno Plugin.
4. **Input Data in JSON Format**: Input your data, following the JSON structure. This data should ideally be provided by a developer to align with the backend data structures.
5. **Save Your Changes**: Click the Save button at the bottom of the tab to apply your modifications.

> [!NOTE]
> The DataContext content is linked to the Root Frame in Figma. This means the data is stored in the first root frame of the Figma file, regardless of the currently selected element.

### Benefits of Using the DataContext Feature

The DataContext tab is vital for developers and designers to visualize and test how data-driven components of the UI will behave and look. By using developer-provided JSON, the fidelity of the design-to-development workflow is enhanced, ensuring the UI is not only visually appealing but also aligns perfectly with backend data structures.

Leverage the DataContext tab in the Uno Figma Plugin for accurate and functional UI designs, ensuring a smooth transition from design to code.

---
uid: Uno.Figma.Learn.Designers.ItemsRepeater
---

# Using the ItemsRepeater Property 

## What are they, and why use them?

ItemsRepeater is a feature that generates code for displaying a collection of items in customizable layouts, such as lists and grids. It allows for the efficient display of large data sets by rendering items in a repeating layout, improving performance and reducing memory usage in generated apps. This can be beneficial for developers and streamlines the handoff process. ItemsRepeater also supports external data sources and bindings through the Uno plugin, enabling realistic previews and optimal layout design before handoff.

The use of ItemsRepeater ensures consistent design, reduces maintenance by updating only one item for changes, and maximizes the amount of generated code to jumpstart development.

## How to Apply ItemsRepeater to Your Figma Designs

1. Select the frame for the repeated items.
2. Launch the Uno Figma plugin.
3. In the *Properties* Tab, from the *Type* dropdown menu, select **ItemsRepeater**.
4. Go to the *Data Context* Tab and enter data in JSON format.
5. Click the *Save* button at the bottom of the tab.
6. In the *Preview* Tab, click the Refresh button to update the layout with the data context.
7. The live preview will now show the layout with data from the Data Context tab.

![](assets/ItemsRepeater.png)

> [!NOTE] 
> ItemsRepeater does not provide states for repeated items. The *Data Context* is set at the *Root Frame* in Figma, so the data will be saved to the first *root* frame in the Figma data, regardless of the selected element.

### Data Context Example (used in the above screenshot)

``` json
{
  "Items": [
    {
      "Name": "Alpine Trek Jacket - Men's",
      "Brand": "Mountain Peak",
      "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product1.png",
      "DiscountedPrice": "$200.99",
      "Discount": "40% OFF"
    },
    {
      "Name": "Velocity Sprinter Shoes",
      "Brand": "RunFast Gear",
      "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product2.png",
      "DiscountedPrice": "$120.49",
      "Discount": "Save 30%"
    },
    {
      "Name": "Eagle Hiker Running Shoes",
      "Brand": "Outdoor Ventures",
      "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product3.png",
      "DiscountedPrice": "$175.00",
      "Discount": "Save 15%"
    },
    {
      "Name": "Rapid Trail Runner",
      "Brand": "TrailMaster",
      "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product4.png",
      "DiscountedPrice": "$89.99",
      "Discount": "Save 20%"
    },
    {
      "Name": "Marathon Elite Sneakers",
      "Brand": "CityGear",
      "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product5.png",
      "DiscountedPrice": "$59.99",
      "Discount": "HOT DEAL"
    }
  ]
}
```


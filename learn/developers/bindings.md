---
uid: Uno.Figma.Learn.Developers.Bindings
---

# Bindings

## Overview

The plugin allow users to bind data from a Json file directly to the preview result. This feature is very useful to verify the result of a listing or even to generate a better preview of the generated screen.

## How it works?

To bind data to a control, first it is necessary to add a Json content to  [DataContext Tab](datacontext-tab.md).
Let's take the following code as example:

``` json
{
  "StoreName" : "Uno Shoes Store",
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
    }
  ]
}
``` 

Considering a screen with a TextBlock which will represent the name of the Store and an ItemsRepeater, containing another TextBlock which will repeat the Product List (a list of the product names), lets configure the bindings.

### Steps to configure Content Expressions
1 - Add the Json code to the DataContext Tab and save
2 - Select the TextBlock Store Name and navigate to the Properties Tab
3 - Fill the Content field with `{StoreName}`
4 - Select now the ItemsRepeater frame. Set the Type field as **ItemsRepeater(StackLayout)** and the Content field as `{Items}` 
5 - Select now the TextBlock for the Product Name, inside the ItemsRepeater and set the Content field as `{Name}`
6 - Navigate to Preview Tab and press refresh to see the result


> [!NOTE]
> To know more about how to generate ItemsRepeater in the plugin, please refer to [ItemsRepeater](../designers/items-repeater.md).
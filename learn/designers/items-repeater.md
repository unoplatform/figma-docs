# Using the ItemsRepeater property 

An advanced feature for designers requires some knowledge of JSON.

## What are they, and why use them?

ItemsRepeater generates code that allows you to display a collection of items in a customizable layout that can be repeated multiple times, think lists, and grids.

The key benefit of using the ItemsRepeater control is that it allows you to display large amounts of data smartly and efficiently. Rather than creating a separate UI element for each item in a collection, you can use the ItemsRepeater property to render the items in a repeating layout, which can improve performance and reduce memory usage in your generated apps. This will be a gain for your fellow developers and make handoff easier. Pair this with the ability to set bindings through the Uno plugin and use external data sources to populate text and images in your repeated items to produce more realistic previews that can assist you in catching issues and creating the optimal layout for your data set before the handoff.

ItemsRepeater helps generate consistent design, minimizes maintenance as you only have one item to update when changes are required, and maximizes the amount of code generated you generate to kick-start development.

## How to apply itemsRepeater to your Figma designs

1. Select the frame you want the repeated Items generated into;

2. Launch the Uno Figma plugin;

3. In *Properties* Tab from the *Type* dropdown menu, select **ItemsRepeater**;

4. Go to the *Data* *Context* Tab and make changes - follow the JSON format;

5. Click the *Save button* at the bottom of the tab.

6. Go to the *Preview* Tab and click the Refresh button at the bottom of the tab

7. The live preview now allows you to scroll through the updated layout reflecting the information from the data context tab (example provided below)

![](assets/ItemsRepeater.png)

> [!NOTE] 
> ItemsRepeater does not provide states for repeated items.
 
The content of the *Data Context* is set at the *Root Frame* in Figma. It means no matter which element is currently selected, the data will be saved into the first *root* frame in the Figma data.


Data Context Example (used in the above screenshot)

```json
 "Items": [
 {
 "Name": "Carto Triclimate Jacket - Men's",
 "Brand": "The North Face",
 "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product1.png",
 "DiscountedPrice": "$251.24",
 "Discount": "50% OFF"
 }, {
 "Name": "Gel-Kayano 27 Running Shoes",
 "Brand": "ASICS",
 "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product2.png",
 "DiscountedPrice": "$149.99",
 "Discount": "Save 25%"
 }, {
 "Name": "Gel-Kayano 27 Running Shoes",
 "Brand": "ASICS",
 "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product3.png",
 "DiscountedPrice": "$149.99",
 "Discount": "Save 10%"
 }, {
 "Name": "Gel-Kayano 27 Running Shoes",
 "Brand": "ASICS",
 "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product4.png",
 "DiscountedPrice": "$149.99",
 "Discount": "Save 15%"
 }, {
 "Name": "Gel-Kayano 27 Running Shoes",
 "Brand": "ASICS",
 "Photo": "https://nv-assets.azurewebsites.net/tests/commerce/products/product5.png",
 "DiscountedPrice": "$149.99",
 "Discount": "HOT DEAL"
 }
 ]
}
```


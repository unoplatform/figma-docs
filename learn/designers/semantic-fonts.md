# How to Use Fonts

Uno Toolkit comes pre-loaded with 19 semantic font styles to ensure your project will look great on any target platform. All the Toolkit components use these styles and the plugin can generate the necessary XAML for all of them with zero extra effort on your part.

## General Guidelines

- Each native platform uses a different default font, make sure you download the proper fonts for your project from their respective providers:
            \- Material [Roboto](https://fonts.google.com/specimen/Roboto)
            \- Cupertino [SF-Pro](https://developer.apple.com/fonts/)
            \- Fluent [SegoeUI-Variable and Static Fonts](https://docs.microsoft.com/en-us/windows/apps/design/downloads/#fonts)

Uno will apply the proper native fonts, sizings, and spacings based on the Toolkits semantic text styles used in your design.
To apply a text style to a custom layout follow the steps below.

## Steps

1. Select text layer (If it has no style applied already go to step 2, else go to step 3)
2. From the *Text* section of the Figma `Design` panel and click the `Style` button
3. Click on the desired style from the Text Style Panel

![](assets/fonts.png)

## Toolkit Type Styles

```
Display Large
Display Medium
Display Small

Headline Large
Headline Medium
Headline Small

Title Large
Title Medium
Title Small

Label Large
Label Medium
Label Small
Label Extra Small

Body Large
Body Medium
Body Small

Caption Large
Caption Medium
Caption Small
```

## Overriding Font Styles. 

Uno Plugin allows some changes on semantic font styles.
Changing the following properties will add new entries on generated Xaml resources to override default Toolkit styles values:

- Font Height
- Font Weight

   > [!IMPORTANT]
   > **Don't rename semantic font styles**. Uno Plugin uses the type styles name as reference to match with default styles from Toolkit. If you rename a type style, the plugin will not be able to generate the proper Xaml code.
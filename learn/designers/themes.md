# Color Themes

## How to Generate Color Themes?

Toolkit provides Light and Dark themes that should work for any project. They can be customized to follow to colors required by a particular project. In the case where there is no predefined color theme or simply to help fill in the gaps for an existing color theme, we recommend using a tool like the **Material theme Builder**.

You can also swap color themes in and out of the document using the **Atlas Theme Manager Plugin**.

More details to get those tools on the [Download & Tools](../../download.md) page.

## How to generate a Theme Package?

Uno Figma Plugin allows you to import theme packages to customize your Figma FIle. The **Material theme Builder** tool can customize a theme and generate a theme package that can be imported into your Figma file, through Uno Plugin.

## Steps

1. Access web version of **Material theme Builder Tool**.
2. **Customize your theme** the way your project requires. You can also create custom colors which will be imported as well.
3. Go to **Export** section and select **Material Tokens** option to download your package.

> [!CAUTION]
> Till the time we wrote this document, the Material theme Builder tool does not support importing back your theme package. So, if you want to make changes to your theme, you will have to start from scratch or leave the Theme Builder web page open.

## How to import a Theme Package?

### Steps

1. Open your Figma file and select **Uno Plugin** from the Plugins menu.
2. Access the **Properties Tab** and go to **Theme Package** section.
3. Click at the **Import** button and select the theme package you downloaded from the Material website. You can select the entire original zip file or the json file accordingly to the package format you selected.
4. Then confirm your choice and your theme will be applied to your Figma file.

> [!TIP]
> If something is not as you expected, a simple **Undo** can remove all imported changes at once.

> [!TIP]
> The plugin will ignore any file if its content is not relevant to the theme and will throw a warning message in that case.
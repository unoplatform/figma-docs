---
uid: Uno.Figma.Learn.Designers.TypeScaleOverrides
---

# How to Override Type Sizing
**Advanced Feature**

## Overview

The Uno Figma Platform Material Toolkit (UFPMT) includes a comprehensive set of Type Styles that define the sizes, weights, and font families used throughout the design system. With recent updates, UFPMT now supports changing the size, weight, and font family of all its preset Type Styles.

> [!IMPORTANT]
> Please note that modifying a Type Style affects all components that utilize it in the file. This is a global change, not an instance-specific override.

## How It Works

Modifying Type Styles can significantly impact your design, so it's crucial to proceed with caution:

1. **Locate the Text Styles**: In the *Design* Pane, expand the *Uno Semantic* grouping to view the list of type styles.
2. **Access Settings**: Hover over the type style you wish to edit until the *Settings* icon appears, then click on it.
3. **Edit Text Style**: In the *Edit text style* panel, you can now change the font's weight, size, and family. Your design will begin to adjust immediately. Feel free to modify as many styles as required for your project.

![Type Style Overrides](assets/TypeStyleOverrides.png)

> [!NOTE] 
> Overrides for line height and character spacing are not currently supported when generating code from Figma.

## Components Without Support for Text Style Override

Some components may not respond well to text style overrides, leading to unusual reflows or no change. These components include:

- DatePicker
- PersonPicture
- RatingControl
- SwipeControl

For these components, it's advisable to use the default type settings for optimal consistency and functionality.

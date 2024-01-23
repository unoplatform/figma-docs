---
uid: Uno.Figma.Overview.FAQ
---

# FAQ - Figma Plugin

## Is paid version of Figma required?

No, the free version of Figma is sufficient to use the plugin. Some Figma features are only available in the paid version, but they are not required to use the plugin.

## Is the plugin available in the desktop version of Figma?

Yes, the plugin is available in both the web and desktop versions of Figma. The usage is the same in both versions.

## Should the plugin be used while running Figma in _developer mode_ or _design mode_?

The plugin works in both modes and the features are the same. Launching it is slightly different in each mode and it is not appearing in the same place.

Using design mode, the plugin is launched from the _Plugins_ menu in the toolbar and shown in a floating window.

Using developer mode, the plugin is launched from the _Plugins_ tab in the right panel and shown in the same side panel.

## Is it possible to generate C# Markup instead of XAML?

Yes, it is possible to generate [C# Markup](xref:Uno.Extensions.Markup.Overview) instead of XAML. Directly from the _Export_ tab, select the _C# Markup_ option.

The settings will give more C# Markup generation options.

## Can the plugin generate code using controls from my own library?

Yes, it is possible to reference your own controls in the generated code. You will need to create [Custom Components](xref:Uno.Figma.Learn.Developers.CustomComponents) and you will be able to use and reuse them at will in your designs.

The previewer won't be able to render them, but the generated code will be correct and will compile. A placeholder will be rendered in the previewer.

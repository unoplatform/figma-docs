# Starting a New Design and General Tips

To ensure you get proper XAML and previews from the plugin please follow these guidelines:


1. Duplicate the Uno Toolkit for Figma, you can find [here](https://www.figma.com/community/file/1045411863379988189/Uno-Platform-Material-Toolkit). First rename it and change the cover image then **work from the provided file**. Do not copy paste elements from the toolkit into your own files as the plugin does not support your existing design files. 
             
   **Important**: Do not use the Uno Toolkit as a Figma Library linked to a new file nor to an existing Figma file. Referenced components and styles will     not render proper code from a new file. Always start work within the provided file.
              

1. **Use the provided** **Colour Styles**. Follow the *Getting Started Instructions* provided with the Toolkit to learn how to update the HEX values of the included semantic colour styles.
   
2. **Use the provided** **Type Styles**. Uno Toolkit does not currently support custom fonts, nor custom sizes. You may include custom fonts in your design of course, but the XAML for these will not be generated on export.
   
3. **Use Page Templates**. We provide handy templates that include all the proper layer structures to generate XAML and preview of your designs through the plugin. Just pick the template you need from the *Assets* section in Figma, drag it to the work canvas and *Detach the instance* to have a fully     functional page ready to work with. **Page instances must always be detached from their** **Template Masters** to function properly with the *Uno* *Toolkit*.
   
4. **Always use** **Auto layouts** for optimal rendering when placing components into your layouts. The same applies when using custom components or layouts always. Toolkit rendering does not support elements positioned with absolute (*X,Y*) coordinates.

**Links**

Download [[Uno Figma Toolkit](https://www.figma.com/community/file/1045411863379988189/Uno-Platform-Material-Toolkit)] [link to be updated]

Download the [[Uno Plugin for Figma](https://www.figma.com/community/plugin/1045528009520465828)] 


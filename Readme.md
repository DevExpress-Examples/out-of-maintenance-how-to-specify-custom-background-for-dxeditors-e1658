<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128645006/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1658)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/WpfApplication64/Window1.xaml) (VB: [Window1.xaml](./VB/WpfApplication64/Window1.xaml))
<!-- default file list end -->
# How to specify custom background for DXEditors


<p>In our themes, the Control.BackgroundProperty is defined by several elements with different colors, gradients, margins, paddings and corner rounding. You can't specify this complex functionality with only the Control.BackgroundProperty property. You can implement your own template using the TextEditThemeKey key ({dxet:TextEditThemeKey ResourceKey=BorderTemplate}). Also, you need to bind to the Background property.</p>

<br/>



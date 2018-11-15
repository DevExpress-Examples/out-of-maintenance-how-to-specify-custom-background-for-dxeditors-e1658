<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/WpfApplication64/Window1.xaml) (VB: [Window1.xaml](./VB/WpfApplication64/Window1.xaml))
<!-- default file list end -->
# How to specify custom background for DXEditors


<p>In our themes, the Control.BackgroundProperty is defined by several elements with different colors, gradients, margins, paddings and corner rounding. You can't specify this complex functionality with only the Control.BackgroundProperty property. You can implement your own template using the TextEditThemeKey key ({dxet:TextEditThemeKey ResourceKey=BorderTemplate}). Also, you need to bind to the Background property.</p>

<br/>



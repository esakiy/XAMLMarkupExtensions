# XAML Markup Extensions for WPF #

## Key features ##

* Full support of nested markup extensions
* A couple of interesting markup extensions
* Multiple UI threads

## Content ##

### XAMLMarkupExtensions.Base ###

* INestedMarkupExtension:
  Interface that has to be implemented to add the nesting feature to other classes derived from MarkupExtension.

* NestedMarkupExtension:
  A default implementation of the INestedMarkupExtension interface. We suggest to use this class to design nestable markup extensions.

* ObjectDependencyManager and SimpleProvideValueServiceProvider:
  Internal used helper classes.

* ParentChangedNotifier:
  Helper class for changes on the Parent property of FrameworkElement objects.
  
* Type, Static & Null extension (known from WPF)

### XAMLMarkupExtensions.Binding ###

* DynBindingExtension:
  A markup extension that can change the source and/or path of a binding.

* BindingProxy:
  Internal used helper class.

### XAMLMarkupExtensions.Strings ###

* CatExtension:
  Concatenate strings coming from various sources.

### XAMLMarkupExtensions.Design ###

* AlternatingGridColorExtension:
  Return a specific color for odd and even rows in grids.

To Be Continued...
(contributions are welcome)

## NuGet Package ##

https://www.nuget.org/packages/XAMLMarkupExtensions

## License ##

[MS-PL](https://github.com/MrCircuit/XAMLMarkupExtensions/blob/master/LICENSE)

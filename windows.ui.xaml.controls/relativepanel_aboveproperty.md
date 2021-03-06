---
-api-id: P:Windows.UI.Xaml.Controls.RelativePanel.AboveProperty
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Xaml.DependencyProperty AboveProperty { get; }
-->

# Windows.UI.Xaml.Controls.RelativePanel.AboveProperty

## -description
Identifies the [RelativePanel.Above](/uwp/api/windows.ui.xaml.controls.relativepanel#xaml-attached-properties) XAML attached property.

Equivalent WinUI property: [Microsoft.UI.Xaml.Controls.RelativePanel.AboveProperty](/windows/winui/api/microsoft.ui.xaml.controls.relativepanel.aboveproperty).

## -property-value
The identifier for the [RelativePanel.Above](/uwp/api/windows.ui.xaml.controls.relativepanel#xaml-attached-properties) XAML attached property.

## -remarks
This property is only an identifier for the property system, and isn't used in most app scenarios. In most cases you set the [RelativePanel.Above](/uwp/api/windows.ui.xaml.controls.relativepanel#xaml-attached-properties) XAML attached property in XAML and won't need this identifier.

To access the [RelativePanel.Above](/uwp/api/windows.ui.xaml.controls.relativepanel#xaml-attached-properties) attached property in code, you can use the dependency property system, calling either [GetValue](../windows.ui.xaml/dependencyobject_getvalue_1188551207.md) or [SetValue](../windows.ui.xaml/dependencyobject_setvalue_52578133.md) and passing RelativePanel.AboveProperty as the dependency property identifier. Another way to get or set the value in code is to use [GetAbove](relativepanel_getabove_1952075081.md) and [SetAbove](relativepanel_setabove_833606851.md).

## -examples
```csharp

// To remove a value, pass null.
Button1.SetValue(RelativePanel.AboveProperty, null);

// To set a value. (Sets Button1 above Button2.)
Button1.SetValue(RelativePanel.AboveProperty, Button2); 

// To get a value. (elementName == "Button2" when set as shown previously.)
string elementName = (string)Button1.GetValue(RelativePanel.AboveProperty);
```



## -see-also
[RelativePanel.Above](/uwp/api/windows.ui.xaml.controls.relativepanel#xaml-attached-properties), [Attached properties overview](/windows/uwp/xaml-platform/attached-properties-overview)

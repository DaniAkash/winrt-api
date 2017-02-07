---
-api-type: winrt class
---
 Create a specialized [InkDrawingAttributes](inkdrawingattributes.md) object through the [CreateForPencil](inkdrawingattributes_createforpencil.md) method.
 Set some general stroke attributes, such as [Color](inkdrawingattributes_color.md) and [Size](inkdrawingattributes_size.md).
 If [InkDrawingAttributesKind](inkdrawingattributeskind.md) is [Pencil](inkdrawingattributeskind.md), set the [Opacity](inkdrawingattributespencilproperties_opacity.md) attribute.
 Call [UpdateDefaultDrawingAttributes](inkpresenter_updatedefaultdrawingattributes.md) to set the [InkDrawingAttributes](inkdrawingattributes.md) used by the [InkPresenter](inkpresenter.md) when rendering a new [InkStroke](inkstroke.md) on an [InkCanvas](../windows.ui.xaml.controls/inkcanvas.md) control.
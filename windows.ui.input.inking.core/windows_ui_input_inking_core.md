---
-api-id: N:Windows.UI.Input.Inking.Core
-api-type: winrt namespace
---

# Windows.UI.Input.Inking.Core

## -description
Overrides default [InkPresenter](../windows.ui.input.inking/inkpresenter.md) run-time behavior to provide advanced input, processing, and management support for Windows Ink apps.

> [!IMPORTANT]
> [Windows.UI.Input.Inking.Core](windows_ui_input_inking_core.md) processing occurs on the ink background thread. For this reason, ensure any custom processing of ink input is as lightweight as possible to avoid degraded performance and to keep your app as responsive as possible.

## -remarks
Standard [InkPresenter](../windows.ui.input.inking/inkpresenter.md) events occur after ink strokes have been rendered.

The [Windows.UI.Input.Inking.Core](windows_ui_input_inking_core.md) API enable you to:
+ Intercept raw pointer data and suppress, or cancel, ink rendering at any point along a stroke. This can be useful when protecting existing ink strokes or providing custom gesture support, such as press and hold, without creating ink artifacts.
+ Control the rendering path of an ink stroke. This can be useful for auto-correcting a user's stroke or masking areas of the drawing surface.


## -examples

## -see-also
[Pen and stylus interactions](http://msdn.microsoft.com/library/3da4f2d2-5405-42a1-9ed9-3a87bcd84c43), [Ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620308), [Simple ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620312), [Complex ink sample](http://go.microsoft.com/fwlink/p/?LinkID=620314)
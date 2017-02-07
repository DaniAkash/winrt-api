---
-api-type: winrt property
---
 If you're modifying a default [ControlTemplate](controltemplate.md), be sure to set the [UseSystemFocusVisuals](control_usesystemfocusvisuals.md) property to **false** to turn off the system focus visuals. When set to **false**, the focus states in the [VisualStateManager](../windows.ui.xaml/visualstatemanager.md) are called.
 Define a [VisualStateGroup](../windows.ui.xaml/visualstategroup.md) for `FocusStates`.
 In the `FocusStates` group, define [VisualState](../windows.ui.xaml/visualstate.md) s for `Focused`, `Unfocused`, and `PointerFocused`.
 Define the focus visuals.
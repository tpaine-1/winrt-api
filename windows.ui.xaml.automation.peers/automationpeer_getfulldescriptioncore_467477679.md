---
-api-id: M:Windows.UI.Xaml.Automation.Peers.AutomationPeer.GetFullDescriptionCore
-api-type: winrt method
---

<!-- Method syntax
virtual protected string GetFullDescriptionCore()
-->

# Windows.UI.Xaml.Automation.Peers.AutomationPeer.GetFullDescriptionCore

## -description
Provides the peer's behavior when a Microsoft UI Automation client calls [GetFullDescription](automationpeer_getfulldescription.md) or an equivalent Microsoft UI Automation client API.

## -returns
A localized string that describes the actual visual appearance or contents of something such as an image or image control.

## -remarks
You should never invoke the base behavior, and all custom peers should override [GetFullDescriptionCore](automationpeer_getfulldescriptioncore.md) to report the full description of this [AutomationPeer](automationpeer.md). For more info, see [Custom automation peers](http://msdn.microsoft.com/library/aa8da53b-fe6e-40ac-9f0a-cb09637c87b4).

## -examples

## -see-also
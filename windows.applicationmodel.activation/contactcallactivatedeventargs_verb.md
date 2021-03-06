---
-api-id: P:Windows.ApplicationModel.Activation.ContactCallActivatedEventArgs.Verb
-api-type: winrt property
---

<!-- Property syntax
public string Verb { get; }
-->

# Windows.ApplicationModel.Activation.ContactCallActivatedEventArgs.Verb

## -description
Gets the action to be performed.

## -property-value
The action to be performed.

## -remarks
Use the Verb property to determine the action to perform when your app is activated with [ActivationKind.Contact](activationkind.md). For call activations, the Verb property is set to the value of [Windows.ApplicationModel.Contacts.ContactLaunchActionVerbs.Call](../windows.applicationmodel.contacts/contactlaunchactionverbs_call.md).

For info about how to handle app activation through contact actions, see [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518236(v=win.10)) and [Quickstart: Handling contact actions ](https://docs.microsoft.com/previous-versions/windows/apps/dn518338(v=win.10)).

## -examples

## -see-also
[Handling Contact Actions sample](https://go.microsoft.com/fwlink/p/?LinkID=320151)

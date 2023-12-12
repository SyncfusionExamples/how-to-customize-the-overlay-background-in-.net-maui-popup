# how-to-customize-the-overlay-background-in-.net-maui-popup
This example demonstrates about how to customize the overlay of PopupView in .NET MAUI Popup (SfPopup).

# Customizing Overlay Background in .NET MAUI SfPopup

In  [.NET MAUI SfPopup](https://www.syncfusion.com/maui-controls/maui-popup) (SfPopup) control provides a flexible way to customize is the overlay background. This article will guide you through the process of either removing the overlay or changing its color.

**Removing the Overlay**

To remove the overlay background, set the `ShowOverlayAlways` property to `False`. By default, this property is set to `True`, which means the overlay is visible whenever the popup is active.

Here's how you can disable the overlay in XAML:

```xaml
<sfPopup:SfPopup x:Name="popup"
                 ShowOverlayAlways="False"/>
```

With this setting, the popup will appear without the dimmed overlay background.

**Changing Overlay Color**

If you prefer to change the color of the overlay instead of removing it, you can use the `OverlayColor` property within the `PopupStyle`.

Here's an example of how to set a custom color for the overlay in XAML:

```xaml
<sfPopup:SfPopup x:Name="popup">
    <sfPopup:SfPopup.PopupStyle>
        <sfPopup:PopupStyle OverlayColor="LightPink" />
    </sfPopup:SfPopup.PopupStyle>
</sfPopup:SfPopup>
```

This will change the overlay background to a light pink color when the popup is displayed.

[View sample in GitHub](https://github.com/SyncfusionExamples/how-to-customize-the-overlay-background-in-.net-maui-popup)

**Conclusion**
I hope you enjoyed learning about How to customize Overlay background in .NET MAUI Popup (SfPopup)
You can refer to our  [.NET MAUI SfPopup](https://www.syncfusion.com/maui-controls/maui-popup) feature tour page to know about its other groundbreaking feature representations and documentation, and how to quickly get started for configuration specifications. You can also explore our .NET MAUI SfPopup example to understand how to create and present data. For current customers, you can check out our components from the License and Downloads page. If you are new to Syncfusion, you can try our 30-day free trial to check out our other controls.
If you have any queries or require clarifications, please let us know in the comments section below. You can also contact us through our support forums, Direct-Trac, or feedback portal. We are always happy to assist you!


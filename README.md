# Azure Intune AppConfig Samples

These samples give you an overview about all possible app configuration policies for iOS and Android Apps. The samples are useful for both device enrollment types managed devices and managed Apps. The configuration settings format is JSON data for Android and XML data for iOS. 

The following app samples are currently available (04/20/20):
- Microsoft Edge
- Microsoft Outlook

More are planned. 

## Getting Started

You can download your preferred samples and adjust them via [text editor](https://notepad-plus-plus.org/downloads/) according to your company details. 

Each operating system folder contains a blank sample that can be used to create a custom JSON or XML data file. These blank samples show you the syntax. 

Note: The boolean key settings must be false or true, only one value is required. The samples show you both option in one line, e.g.:
```
- Android: "valueBool": true|false
- iOS: <true/>|<false/>
```

Your custom JSON or XML data file must be imported via Azure Intune App Configuration Policies for the selected app.

[More information about App Configuration Policies](https://docs.microsoft.com/en-us/mem/intune/apps/app-configuration-policies-overview)

# Azure Intune AppConfig Known Issues

The setting for Edge homepage and managed bookmarks are not working for managed devices & apps, maybe there is a syntax error or application issue. 


## References 

- [How to configure Microsoft Edge](https://docs.microsoft.com/en-us/mem/intune/apps/manage-microsoft-edge)
- [How to configure Microsoft Outlook](https://docs.microsoft.com/en-us/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/outlook-for-ios-and-android-configuration-with-microsoft-intune)
- [Android Chrome Enterprise policy List](https://cloud.google.com/docs/chrome-enterprise/policies/)

# 

Cheers,
[Daniel Weppeler](https://danielweppeler.de)

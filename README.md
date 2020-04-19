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


# Azure Intune AppConfig Known Issues

The setting for Edge homepage and managed bookmarks are not working for managed devices & apps, maybe there is a syntax error or application issue. 


## Link 

Edge
Android Chrome Enterprise policy List: https://cloud.google.com/docs/chrome-enterprise/policies/

# 

Cheers,
[Daniel Weppeler](https://twitter.com/_danielwep/)
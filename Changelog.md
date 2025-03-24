Change history
--------------
* **Version 1.4.11 (2025-03-24)**: Toggle visiblity
* **Version 1.4.7.0 (2024-06-04)**: Updated NuGet packages, fixes https://github.com/serilog-contrib/Serilog.Sinks.MicrosoftTeams.Alternative/issues/32.
* **Version 1.4.6.0 (2024-05-16)**: Removed support for Net7.0.
* **Version 1.4.5.0 (2024-04-22)**: Updated NuGet packages, fixes https://github.com/serilog-contrib/Serilog.Sinks.MicrosoftTeams.Alternative/issues/31.
* **Version 1.4.4.0 (2024-03-03)**: Updated NuGet packages.
* **Version 1.4.3.0 (2023-11-30)**: Added custom exception to handle error codes better in failure callback.
* **Version 1.4.2.0 (2023-11-30)**: Fixed issue with System.Runtime, https://github.com/serilog-contrib/Serilog.Sinks.MicrosoftTeams.Alternative/issues/30.
* **Version 1.4.1.0 (2023-11-23)**: Tried to fix issue with System.Runtime, https://github.com/serilog-contrib/Serilog.Sinks.MicrosoftTeams.Alternative/issues/30.
* **Version 1.4.0.0 (2023-11-21)**: Updated NuGet packages, removed support for NetCore3.1, removed support for netstandard, added support for Net8.0.
* **Version 1.3.0.0 (2022-11-20)**: Updated NuGet packages, removed support for Net5.0, added support for Net7.0.
* **Version 1.2.20.0 (2022-10-30)** : Updated NuGet packages.
* **Version 1.2.19.0 (2022-10-18)** : Wrap exception into code block (Thanks to [mggrand](https://github.com/mggrand)), updated NuGet packages.
* **Version 1.2.18.0 (2022-08-31)** : Updated NuGet packages.
* **Version 1.2.17.0 (2022-08-03)** : Updated NuGet packages.
* **Version 1.2.16.0 (2022-06-01)** : Updated NuGet packages, added filter on property and multi channel support.
* **Version 1.2.15.0 (2022-04-03)** : Updated NuGet packages, hopefully fixes https://github.com/serilog-contrib/Serilog.Sinks.MicrosoftTeams.Alternative/issues/21.
* **Version 1.2.14.0 (2022-03-02)** : Just a new version because of a NuGet upload issue.
* **Version 1.2.13.0 (2022-02-02)** : Invalid version, something went wrong with NuGet. Don't use this version.
* **Version 1.2.12.0 (2022-02-16)** : NuGet packages updated, added nullable checks, added editorconfig, added file scoped namespaces, added global usings, removed native support for Net Framework (Breaking change), fixed Serilog PeriodicBatchingSink issues.
* **Version 1.2.11.0 (2022-01-12)** : NuGet packages updated.
* **Version 1.2.10.0 (2021-11-09)** : NuGet packages updated, added support for Net6.0.
* **Version 1.2.9.0 (2021-11-04)** : Updated NuGet packages, removed support for netstandard2.0.
* **Version 1.2.8.0 (2021-09-30)** : Smaller changes, added new sink that uses Utf8Json and is only available for NetFramework 4.8.
* **Version 1.2.7.0 (2021-09-12)** : Added functionality to format title with a template (Breaking change!), smaller changes due to move to serilog-contrib organization.
* **Version 1.2.6.0 (2021-09-03)** : Updated license to fit the new owning repository, updated readme and so on to fit new package name.
* **Version 1.2.5.0 (2021-08-09)** : Removed support for soon deprecated NetCore 2.1.
* **Version 1.2.4.0 (2021-07-25)** : Updated NuGet packages, enabled source linking for debugging.
* **Version 1.2.3.0 (2021-06-04)** : Updated NuGet packages.
* **Version 1.2.2.0 (2021-04-29)** : Updated NuGet packages.
* **Version 1.2.1.0 (2021-02-21)** : Updated NuGet packages.
* **Version 1.2.0.0 (2021-01-04)** : Updated NuGet packages, updated project files, updated logging for exceptions in self log, simplified test classes, added hint to reference from Microsoft, added option to use code tags for complex messages to avoid strange formatting.
* **Version 1.1.1.0 (2020-11-19)** : Added output template.
* **Version 1.1.0.0 (2020-11-19)** : Updated NuGet packages, moved to Net 5.0, added possibility to add static buttons to each message (Thanks to [Appelg](https://github.com/Appelg)), added failure callback.
* **Version 1.0.11.0 (2020-07-29)** : Fixed a bug where the omitPropertiesSection flag wasn't set when configuration was read.
* **Version 1.0.10.0 (2020-07-25)** : Fixed a logical error with the messagesToSend list (Thanks to [mahdiman](https://github.com/mahdiman)).
* **Version 1.0.9.0 (2020-07-15)** : Updated NuGet packages, fixed a null reference exception (Thanks to [mahdiman](https://github.com/mahdiman)).
* **Version 1.0.8.0 (2020-06-05)** : Updated NuGet packages, adjusted build to Visual Studio, moved changelog to extra file.
* **Version 1.0.7.1 (2020-06-04)** : Updated NuGet packages, added option for proxy (Thanks to [ruisantos78](https://github.com/ruisantos78)).
* **Version 1.0.7.0 (2020-05-10)** : Updated NuGet packages.
* **Version 1.0.6.0 (2020-03-26)** : Updated NuGet packages.
* **Version 1.0.5.0 (2019-11-08)** : Updated NuGet packages.
* **Version 1.0.3.2 (2019-11-04)** : Adjusted license to the MIT license.
* **Version 1.0.3.1 (2019-10-22)** : Removed invalid fields from nuspec file, added dependency information to NuGet package, added build for netcore.
* **Version 1.0.3.0 (2019-10-15)** : Added option for omitting properties section in message (Thanks to [maestroMike](https://github.com/maestroMike)), added GitVersionTask, updated NuGet packages.
* **Version 1.0.2.1 (2019-06-24)** : Added option to only show from and to dates when the dates are not equal.
* **Version 1.0.2.0 (2019-06-23)** : Fixed icon in NuGet package.
* **Version 1.0.0.1 (2019-06-21)** : Added option for minimal log level.
* **Version 1.0.0.0 (2019-06-21)** : 1.0 release.

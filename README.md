# Uno.Xamarin.Essentials

**Uno.Xamarin.Essentials** is a fork of the [Xamarin.Essentials](https://github.com/xamarin/Essentials) library to enable WebAssembly support for Uno Platform based applications, as well as all the official Xamarin.Essential supported platforms.

To use this library, you'll need to replace your Nuget package references from `Xamarin.Essentials` to `Uno.Xamarin.Essentials`.

## Reporting issues

The implementation of the WebAssembly is provided through the UWP implementation of Xamarin.Essentials. This means that you may find parts that are not implemented, because the WinRT APIs may not yet be implemented in Uno.

If you find such an API, please [open an issue in the Uno Platform repository](https://github.com/unoplatform/uno/issues/new/choose) to let us know about it!

## Xamarin.Essentials Documentation

Xamarin.Essentials gives developers essential cross-platform APIs for their mobile applications. 

iOS, Android, and UWP offer unique operating system and platform APIs that developers have access to, all in C# leveraging Xamarin. It is great that developers have 100% API access in C# with Xamarin, but these APIs are different per platform. This means developers have to learn three different APIs to access platform-specific features. With Xamarin.Essentials, developers have a single cross-platform API that works with any iOS, Android, or UWP application that can be accessed from shared code no matter how the user interface is created.

[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/xamarin/Essentials)

## Documentation

Browse our [full documentation for Xamarin.Essentials](https://docs.microsoft.com/xamarin/essentials), including feature guides, on how to use each feature.

## API Documentation

The following cross-platform APIs are available in Xamarin.Essentials:

* [Accelerometer](https://docs.microsoft.com/xamarin/essentials/accelerometer)
* [App Information](https://docs.microsoft.com/xamarin/essentials/app-information)
* [Battery](https://docs.microsoft.com/xamarin/essentials/battery)
* [Clipboard](https://docs.microsoft.com/xamarin/essentials/clipboard)
* [Compass](https://docs.microsoft.com/xamarin/essentials/compass)
* [Connectivity](https://docs.microsoft.com/xamarin/essentials/connectivity)
* [Device Display Information](https://docs.microsoft.com/en-us/xamarin/essentials/device-display)
* [Device Information](https://docs.microsoft.com/xamarin/essentials/device-information)
* [Email](https://docs.microsoft.com/xamarin/essentials/email)
* [File System Helpers](https://docs.microsoft.com/xamarin/essentials/file-system-helpers)
* [Flashlight](https://docs.microsoft.com/xamarin/essentials/flashlight)
* [Geocoding](https://docs.microsoft.com/xamarin/essentials/geocoding)
* [Geolocation](https://docs.microsoft.com/xamarin/essentials/geolocation)
* [Gyroscope](https://docs.microsoft.com/xamarin/essentials/gyroscope)
* [Launcher](https://docs.microsoft.com/xamarin/essentials/launcher)
* [Magnetometer](https://docs.microsoft.com/xamarin/essentials/magnetometer)
* [MainThread](https://docs.microsoft.com/xamarin/essentials/main-thread)
* [Maps](https://docs.microsoft.com/xamarin/essentials/maps)
* [Open Browser](https://docs.microsoft.com/xamarin/essentials/open-browser)
* [Orientation Sensor](https://docs.microsoft.com/en-us/xamarin/essentials/orientation-sensor)
* [Phone Dialer](https://docs.microsoft.com/xamarin/essentials/phone-dialer)
* [Preferences](https://docs.microsoft.com/xamarin/essentials/preferences)
* [Screen Lock](https://docs.microsoft.com/xamarin/essentials/screen-lock)
* [Secure Storage](https://docs.microsoft.com/xamarin/essentials/secure-storage)
* [Share](https://docs.microsoft.com/xamarin/essentials/share)
* [SMS](https://docs.microsoft.com/xamarin/essentials/sms)
* [Text-to-Speech](https://docs.microsoft.com/xamarin/essentials/text-to-speech)
* [Version Tracking](https://docs.microsoft.com/xamarin/essentials/version-tracking)
* [Vibrate](https://docs.microsoft.com/xamarin/essentials/vibrate)

## Contributing

Please read through our [Contribution Guide](CONTRIBUTING.md). We are not accepting new PRs for full features, however any [issue that is marked as `up for grabs`](https://github.com/xamarin/Essentials/issues?q=is%3Aissue+is%3Aopen+label%3A%22up+for+grabs%22) are open for community contributions. We encourage creating new issues for bugs found during usage that the team will triage. Additionally, we are open for code refactoring suggestions in PRs.
# 👋 Welcome to Socket Mobile's GitHub Channel

This is the public home of CaptureSDK, a unified data capture SDK for accessing and controlling all Socket Mobile devices, including our camera based scanners C820, C860, our hardware products barcode readers, NFC reader/writers, barcode/NFC combo, all in one integration. To learn more about the SDK, check out [the documentation site](https://docs.socketmobile.com/main/en/).

## IMPORTANT NOTE

### CaptureSDK Transition Announcement

Our CaptureSDK is gradually moving from private to public access on GitHub, with platform support being restored incrementally. Developers interested in a specific platform can stay updated by watching the corresponding SDK repository, ensuring they receive immediate notifications about its release.

The other repos are still behind a firewall and require an access token to gain access to them.
Please log to our [Developers Portal](https://www.socketmobile.com/developers/login) to gain access to these repos.

**We will continue to post updates in the README of each repos in this Github account.**

## DON'T MISS OUT

We continue everyday to improve CaptureSDK on all supported platforms. It's important you keep your application up to date with the latest version of CaptureSDK by watching the repos of the platform your application is using.

Staying current with these updates reduces the effort needed between upgrades and ensures more effective data collection with our products.

**We strongly recommend to watch the repositories used by your application.**

## iOS development

|      CaptureSDK     |  Note |
|----------|-------|
| [CaptureSDK - Swift Package Manager](https://github.com/SocketMobile/swift-package-capturesdk) | Swift and Objective C |

NB: Our [CaptureSDK for Cocoapods](https://github.com/SocketMobile/cocoapods-capturesdk) is also available but as Cocoapods is adding a lot complexity in a Xcode project, we strongly recommend Swift Package Manager. You can also mix Swift Package Manager and Cocoapods.
There's no need to migrate all your Cocoapods to Swift Package Manager all at once.

|      Sample     |  Note |
|----------|-------|
| [SingleEntry Swift (Swift Package Manager)](https://github.com/SocketMobile/capturesingleentryswift-ios/tree/swift-package-manager) | Swift and Objective C |

## Android development

|      CaptureSDK     |  Note |
|----------|-------|
| [CaptureSDK - Android](https://github.com/SocketMobile/android-capturesdk) | Java and Kotlin |

This [repository](https://github.com/SocketMobile/samples-android/tree/main/hellocapture) is updated at each release of the CaptureSDK for Android, you can watch for it to not miss out on new releases.

Android SDK is hosted on Maven. Refer to **[this link](https://docs.socketmobile.com/capture/java/en/latest/android/getting-started.html#add-the-sdk-to-your-project)** for how to add the SDK for Android or plain Java development.

|      Sample     |  Note |
|----------|-------|
| [HelloCapture](https://github.com/SocketMobile/samples-android/tree/main/hellocapture) | For barcode scanning |
| [HelloCaptureBLE](https://github.com/SocketMobile/samples-android/tree/main/hellocapture-ble-android) | For NFC reader/writer (Bluetooth LE devices) |

## Windows development

|      CaptureSDK     |  Note |
|----------|-------|
| [CaptureSDK - Windows](https://github.com/SocketMobile/windows-capturesdk) | C# |

Windows CaptureSDK is hosted on Nuget. Refer to **[this link](https://www.nuget.org/packages/SocketMobile.Capture)** for how to add the SDK.

|      Sample     |  Note |
|----------|-------|
| [Single Entry UWP](https://github.com/SocketMobile/capturesingleentry-uwp) | For Windows |

## Cross platform development

|      CaptureSDK     |  Note |
|----------|-------|
| [CaptureSDK - React Native](https://github.com/SocketMobile/react-native-capture) | Javascript / Typescript |
| [CaptureSDK - Flutter](https://github.com/SocketMobile/capturesdk_flutter) | Dart |
| [CaptureSDK - .NET MAUI](https://github.com/SocketMobile/csharp-capturesdk) | C# |

The CaptureSDK for the cross platforms supports SocketCam C820 and C860 and can be installed by following the instructions from our [Developers Portal](https://www.socketmobile.com/developers/login).

The samples below need to be updated with the instructions found in the [Developers Portal](https://www.socketmobile.com/developers/login).

|      Sample     |  Note |
|----------|------|
| [SingleEntry RN](https://github.com/SocketMobile/singleentry-rn) | For iOS and Android |
| [Capture Flutter Sample](https://github.com/SocketMobile/capture_flutter_sdk_sample) | For iOS and Android|
| [Capture .NET MAUI Sample](https://github.com/SocketMobile/capture_maui_sdk_sample) | For iOS, Android and Windows|

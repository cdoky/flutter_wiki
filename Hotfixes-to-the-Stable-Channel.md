In general, our philosophy is to update the `stable` channel on a quarterly basis with feature updates. In the intervening period, occasionally we may decide a bug or regression warrants a hotfix. We tend to be extremely conservative with these hotfixes, since there's always a risk that fixing one bug introduces a new one, and we want the `stable` channel to always represent our most tested builds. 

We intend to announce hotfixes to the [flutter-announce](https://groups.google.com/forum/#!forum/flutter-announce) group, and we recommend that you subscribe to that list if you publish an application using Flutter. 

Note that we only hotfix the latest version -- if you see bugs on older versions of the `stable` channel, please consider moving to the latest `stable` channel version. 

To ensure that you have the latest stable version with the hotfixes listed below, use the flutter tool at the command line as follows:

```
$ flutter channel stable
$ flutter upgrade
```
## Flutter 3.0 Changes
### [3.0.1](https://github.com/flutter/flutter/releases/tag/3.0.1) (May 19, 2022)
This hotfix release addresses the following issues:
 * [flutter/102947](https://github.com/flutter/flutter/issues/102947) - Radial gradients behave incorrectly when painting text.
### [3.0.0](https://github.com/flutter/flutter/releases/tag/3.0.0) (May 11, 2022)
Initial stable release.
## Flutter 2.10 Changes
### [2.10.5](https://github.com/flutter/flutter/releases/tag/2.10.5) (April 18, 2022)
This hotfix release addresses the following issues:
 * [flutter/101224](https://github.com/flutter/flutter/issues/101224) - Flutter web debugger fails when using chrome 100 or greater. 
### [2.10.4](https://github.com/flutter/flutter/releases/tag/2.10.4) (March 28, 2022)
This hotfix release addresses the following issues:
 * [flutter/93871](https://github.com/flutter/flutter/issues/93871) - Custom embedders fail to build when using default sysroot (GCC 11).
 * [dart/48559](https://github.com/dart-lang/sdk/issues/48559) - Flutter web apps crash when using package:freezed.
### [2.10.3](https://github.com/flutter/flutter/releases/tag/2.10.3) (March 02, 2022)
This hotfix release addresses the following issues:
 * [flutter/98973](https://github.com/flutter/flutter/issues/98973) - Deadlock in application startup in profile/release mode.
 * [flutter/98739](https://github.com/flutter/flutter/issues/98739) - ios: Visual glitch when scrolling a list in a Scaffold that has a Material and Container as bottomNavigationBar.
 * [flutter/97086](https://github.com/flutter/flutter/issues/97086) - Windows: Fail to launch app in debug mode.
### [2.10.2](https://github.com/flutter/flutter/releases/tag/2.10.2) (February 18, 2022)
This hotfix release addresses the following issues:
 * [flutter/95211](https://github.com/flutter/flutter/issues/95211) - Transform animation with BackdropFilter is causing a crash.
 * [flutter/98155](https://github.com/flutter/flutter/issues/98155) - App crashes after upgrading to 2.10.x using webview + video_player plugin.
 * [flutter/98361](https://github.com/flutter/flutter/issues/98361) - Error in DL bounds calculations causes incorrect SVG rendering.
 * [flutter/97767](https://github.com/flutter/flutter/issues/97767) - New material icons are not properly rendered.
 * [flutter/95711](https://github.com/flutter/flutter/issues/95711) - Linux builds default to building GLFW.
### [2.10.1](https://github.com/flutter/flutter/releases/tag/2.10.1) (February 9, 2022)
This hotfix release addresses the following issues:
 * [flutter/94043](https://github.com/flutter/flutter/issues/94043) - Autofill does not work in `TextField`.
 * [flutter/96411](https://github.com/flutter/flutter/issues/96411) - Safari: Unable to enter text into `TextField`.
 * [flutter/96661](https://github.com/flutter/flutter/issues/96661) - Platform views throw fatal exception: Methods marked with @UiThread must be executed on the main thread.
 * [flutter/97103](https://github.com/flutter/flutter/issues/97103) - Images become corrupted when using CanvasKit.
 * [flutter/97679](https://github.com/flutter/flutter/issues/97679) - Don't remove overlay views when the rasterizer is being torn down.
 * [dart/48301](https://github.com/dart-lang/sdk/issues/48301) - Avoid speculative conversion in ffi Pointer.asTypedList.
### [2.10.0](https://github.com/flutter/flutter/releases/tag/2.10.0) (February 3, 2022)
Initial stable release.
## Flutter 2.8 Changes
### [2.8.1](https://github.com/flutter/flutter/releases/tag/2.8.1) (December 16, 2021)
This hotfix release addresses the following issues:
 * [flutter/94914](https://github.com/flutter/flutter/issues/94914) - Apps using `google_sign_in` or `google_maps` don't build in iOS Simulator on ARM macOS
 * [flutter/90783](https://github.com/flutter/flutter/issues/90783) - In rare circumstances, engine may crash during app termination on iOS and macOS
 * [dart/47914](https://github.com/dart-lang/sdk/issues/47914) - AOT compilation fails with error "Invalid argument(s): Missing canonical name for Reference"
 * [dart/47815](https://github.com/dart-lang/sdk/issues/47815) - Running `dart pub publish` with custom pub package server that has URL containing a path may fail.

### [2.8.0](https://github.com/flutter/flutter/releases/tag/2.8.0) (December 8, 2021)
Initial stable release.

## Flutter 2.5 Changes
### [2.5.3](https://github.com/flutter/flutter/releases/tag/2.5.3) (October 15, 2021)
This hotfix release addresses the following issues:
 * [dart/47321](https://github.com/dart-lang/sdk/issues/47321) - Fix a potential out-of-memory condition with analysis server plugins
 * [dart/47432](https://github.com/dart-lang/sdk/issues/47432) - Fix certificate loading on Windows when there are expired certificates
 * [flutter/83792](https://github.com/flutter/flutter/issues/83792) - Fix HTTPS issue related to: "HttpClient throws Invalid argument(s): Invalid internet address"

### [2.5.2]((https://github.com/flutter/flutter/releases/tag/2.5.2)) (September 30, 2021)
This hotfix release addresses the following issues:
 * [dart/47285](https://github.com/dart-lang/sdk/issues/47285) - Fix a regression to the performance of code completions
 * [dart/47316](https://github.com/dart-lang/sdk/issues/47316) - Dynamic tables in ELF files have invalid relocated addresses
 * [flutter/89912](https://github.com/flutter/flutter/issues/89912) - Building iOS app generates unnecessary Flutter.build folder

### [2.5.1]((https://github.com/flutter/flutter/releases/tag/2.5.1)) (September 17, 2021)
This hotfix release addresses the following issues:
 * [flutter/88767](https://github.com/flutter/flutter/issues/88767) - java.lang.SecurityException: Permission denial crash at launch
 * [flutter/88236](https://github.com/flutter/flutter/issues/88236) - null check exception during keyboard keypress
 * [flutter/88221](https://github.com/flutter/flutter/issues/88221) - Material routes delayed on push and pop
 * [flutter/84113](https://github.com/flutter/flutter/issues/84113) - HTTP exceptions talking to VM Service
 * [flutter/83632](https://github.com/flutter/flutter/issues/83632) - Scroll view velocity too high

### 2.5.0 (September 8, 2021)
Initial stable release. 

## Flutter 2.2 Changes
### [2.2.3](https://github.com/flutter/flutter/pull/85719) (July 2, 2021)
This hotfix release addresses the following issues:
  * [flutter/84212](https://github.com/flutter/flutter/issues/84212) - Upgrading to 2.2.1 cause main.dart to crash
  * [flutter/83213](https://github.com/flutter/flutter/issues/83213) - TextFormField not responding to inputs on Android when typing on Microsoft SwiftKey
  * [flutter/82838](https://github.com/flutter/flutter/issues/82838) - Flutter Web failing to compile with "Undetermined Nullability"
  * [flutter/82874](https://github.com/flutter/flutter/issues/82874) - PopupMenuButton is broken after upgrade to Flutter 2.2.

### [2.2.2](https://github.com/flutter/flutter/pull/84364) (June 11, 2021)
This hotfix release addresses the following issues:
  *  [dart/46249](https://github.com/dart-lang/sdk/issues/46249) - Ensure start/stop file watching requests are run on the dart thread.
  *  [dart/46210](https://github.com/dart-lang/sdk/issues/46210) - Fix an analyze crash when analyzing against package:meta v1.4.0
  *  [dart/46173](https://github.com/dart-lang/sdk/issues/46173) - Merge a3767f7db86a85fcd6201e9357ad47b884002b66 to stable channel (2.13)
  *  [dart/46300](https://github.com/dart-lang/sdk/issues/46300) - Fix OOM VM test (`transferable_throws_oom_test` crashing after upgrade from Ubuntu 16)
  *  [dart/46298](https://github.com/dart-lang/sdk/issues/46298) - Ensure start/stop file watching requests are run on the Dart thread
  *  [flutter/83799](https://github.com/flutter/flutter/issues/83799) - Tool may crash if pub is missing from the artifact cache
  *  [flutter/83102](https://github.com/flutter/flutter/issues/83102) - Generated l10n file is missing ‘intl’ import with Flutter 2.2.0
  *  [flutter/83094](https://github.com/flutter/flutter/issues/83094) - Flutter AOT precompiler crash
  *  [flutter/82874](https://github.com/flutter/flutter/issues/82874) - PopupMenuButton is broken after upgrade to Flutter 2.2.

### [2.2.1](https://github.com/flutter/flutter/pull/83372) (May 27, 2021)
This hotfix release addresses the following issues:
 - [flutter/80978](https://github.com/flutter/flutter/issues/80978) - Error "Command PhaseScriptExecution failed with a nonzero exit code" when building on macOS
 - [dart/45990](https://github.com/dart-lang/sdk/issues/45990) - CastMap performs an invalid cast on 'remove', breaking shared_preferences plugin
 - [dart/45907](https://github.com/dart-lang/sdk/issues/45907) - DDC missing nullability information from recursive type hierarchies
 - [flutter/52106](https://github.com/flutter/flutter/issues/52106) - [Web] Accessibility focus border doesn’t follow when navigating through interactive elements with tab key
 - [flutter/82768](https://github.com/flutter/flutter/issues/82768) - [Web] svgClip memory leak in Canvaskit renderer

### 2.2.0 (May 18, 2021)
Initial stable release.

## Flutter 2.0 Changes
### [2.0.6](https://github.com/flutter/flutter/pull/81508) (April 29, 2021)
This hotfix release addresses the following issue:
 - [flutter/81326](https://github.com/flutter/flutter/issues/81326) - macOS binaries not codesigned
 
### [2.0.5](https://github.com/flutter/flutter/pull/80570) (April 16, 2021)
This hotfix release addresses the following issue:
 - [dart/45306](https://github.com/dart-lang/sdk/issues/45306) - Segmentation fault on specific code

### [2.0.4](https://github.com/flutter/flutter/pull/79486) (April 2, 2021)
This hotfix release addresses the following issues:
 - [flutter/78589](https://github.com/flutter/flutter/issues/78589) - Cocoapod transitive dependencies with bitcode fail to link against debug Flutter framework
 - [flutter/76122](https://github.com/flutter/flutter/issues/76122) - Adding a WidgetSpan widget causes web HTML renderer painting issue
 - [flutter/75280](https://github.com/flutter/flutter/issues/75280) - Dragging the "draggable" widget causes widget to freeze in the overlay layer on Web

### [2.0.3](https://github.com/flutter/flutter/pull/78489) (March 19, 2021)
This hotfix release addresses the following issues:
 - [flutter/75261](https://github.com/flutter/flutter/issues/75261) - Unable to deep link into Android app
 - [flutter/78167](https://github.com/flutter/flutter/issues/78167) - Flutter crash after going to version 2
 - [flutter/75677](https://github.com/flutter/flutter/issues/75677) - NoSuchMethodError: The method 'cancel' was called on null at AnsiSpinner.finish
 - [flutter/77419](https://github.com/flutter/flutter/pull/77419) - Fix Autovalidate enum references in fix data

### [2.0.2](https://github.com/flutter/flutter/pull/77850) (March 12, 2021)
This hotfix release addresses the following issues:
  - [flutter/77251](https://github.com/flutter/flutter/issues/77251) - Flutter may show multiple snackbars when Scaffold is nested 
  - [flutter/75473](https://github.com/flutter/flutter/issues/75473) - CanvasKit throws error when using Path.from
  - [flutter/76597](https://github.com/flutter/flutter/issues/76597) - When multiple Flutter engines are active, destroying one engine causes crash
  - [flutter/75061](https://github.com/flutter/flutter/issues/75061) - '_initialButtons == kPrimaryButton': is not true
  - [flutter/77419](https://github.com/flutter/flutter/pull/77419) - Fix Autovalidate enum references in fix data
  - [dart/45214](https://github.com/dart-lang/sdk/issues/45214) - Bad state exception can occur when HTTPS connection attempt errors or is aborted
  - [dart/45140](https://github.com/dart-lang/sdk/issues/45140) - Uint8List reports type exception while using + operator in null safety mode

### [2.0.1](https://github.com/flutter/flutter/pull/77194) (March 5, 2021)
This hotfix release addresses the following issue:
  - [flutter/77173](https://github.com/flutter/flutter/issues/77173) - Building for macOS target fails when Flutter is installed from website

### 2.0.0 (March 3, 2021)
Initial stable release.

## Flutter 1.22 Changes
### [1.22.6](https://github.com/flutter/flutter/pull/74355) (Jan 25, 2021)
This hotfix release addresses the following issue:
  - [flutter/70895](https://github.com/flutter/flutter/issues/70895) - Build error when switching between dev/beta and stable branches.

### [1.22.5](https://github.com/flutter/flutter/pull/72079) (Dec 10, 2020)
This hotfix release addresses the following issue:
  - [flutter/70577](https://github.com/flutter/flutter/issues/70577) - Reliability regression in the camera plugin on iOS

### [1.22.4](https://github.com/flutter/flutter/pull/70327) (Nov 13, 2020)
This hotfix release addresses the following issues:
  - [flutter/43620](https://github.com/flutter/flutter/issues/43620) - Dart analyzer terminates during development
  - [flutter/58200](https://github.com/flutter/flutter/issues/58200) - Apple AppStore submission fails with error: “The bundle Runner.app/Frameworks/App.framework does not sue Infpport the minimum OS Version specified in the Info.plist”
  - [flutter/69722](https://github.com/flutter/flutter/issues/69722) - Setting a custom observatory port for debugging does not take effect
  - [flutter/66144](https://github.com/flutter/flutter/issues/66144) - Setting autoFillHint to text form field may cause focus issues
  - [flutter/69449](https://github.com/flutter/flutter/issues/69449) - Potential race condition in FlutterPlatformViewsController
  - [flutter/65133](https://github.com/flutter/flutter/issues/65133) - Support targeting physical iOS devices on Apple Silicon

### [1.22.3](https://github.com/flutter/flutter/pull/69234) (October 30, 2020)
This hotfix release addresses the following issues:
  - [flutter/67828](https://github.com/flutter/flutter/issues/67828) - Multiple taps required to delete text in some input fields.
  - [flutter/66108](https://github.com/flutter/flutter/issues/66108) - Reading Android clipboard may throw a security exception if it contains media

### [1.22.2](https://github.com/flutter/flutter/pull/68135)  (October 16, 2020)
This hotfix release addresses the following issues:
  - [flutter/67869](https://github.com/flutter/flutter/issues/67869) - Stylus tap gesture is improperly registered.
  - [flutter/67986](https://github.com/flutter/flutter/issues/67986) - Android Studio 4.1 not properly supported.
  - [flutter/67213](https://github.com/flutter/flutter/issues/67213) - Webviews in hybrid composition can cause a crash.
  - [flutter/67345](https://github.com/flutter/flutter/issues/67345) - VoiceOver accessibility issue with some pages.
  - [flutter/66764](https://github.com/flutter/flutter/issues/66764) - Native webviews may not be properly disposed of in hybrid composition.

### [1.22.1](https://github.com/flutter/flutter/pull/67552) (October 8, 2020)
This hotfix release addresses the following issues:
  - [flutter/66940](https://github.com/flutter/flutter/issues/66940) - autovalidate property inadvertently removed.
  - [flutter/66962](https://github.com/flutter/flutter/issues/66962) - The new --analyze-size flag crashes when used with --split-debug-info
  - [flutter/66908](https://github.com/flutter/flutter/issues/66908) - Flutter Activity causing exceptions in some Android versions.
  - [flutter/66647](https://github.com/flutter/flutter/issues/66647) - Layout modifications performed by background threads causes exceptions on IOS14.

### 1.22.0 (October 1, 2020)
Initial stable release.

## Flutter 1.20 Changes
### [1.20.4](https://github.com/flutter/flutter/pull/65787) (September 15, 2020)
This hotfix release addresses the following issues:
  - [flutter/64045](https://github.com/flutter/flutter/issues/64045) - Cannot deploy to physical device running iOS 14

### [1.20.3](https://github.com/flutter/flutter/pull/64984) (September 2, 2020)
This hotfix release addresses the following issues:
  - [flutter/63876](https://github.com/flutter/flutter/issues/63876) - Performance regression for Image animation.
  - [flutter/64228](https://github.com/flutter/flutter/issues/64228) - WebView may freeze in release mode on iOS.
  - [flutter/64414](https://github.com/flutter/flutter/issues/64414) - Task switching may freeze on some Android versions.
  - [flutter/63560](https://github.com/flutter/flutter/issues/63560) - Building AARs may cause a stack overflow.
  - [flutter/57210](https://github.com/flutter/flutter/issues/57210) - Certain assets may cause issues with iOS builds.
  - [flutter/63590](https://github.com/flutter/flutter/issues/63590) - Passing null values from functions run via Isolates throws an exception.
  - [flutter/63427](https://github.com/flutter/flutter/issues/63427) - Wrong hour/minute order in timePicker in RTL mode.

### [1.20.2](https://github.com/flutter/flutter/pull/63591) (August 13, 2020)
This hotfix release addresses the following issues:
  - [flutter/63038](https://github.com/flutter/flutter/issues/63038) - Crash due to serialization of generic DartType (UnknownType)
  - [flutter/46167](https://github.com/flutter/flutter/issues/46167) - iOS platform view cancels gesture while a new clip layer is added during the gesture
  - [flutter/62198](https://github.com/flutter/flutter/issues/62198) - SliverList throws Exception when first item is SizedBox.shrink()
  - [flutter/59029](https://github.com/flutter/flutter/issues/59029) - build ios --release can crash with ArgumentError: Invalid argument(s)
  - [flutter/62775](https://github.com/flutter/flutter/issues/62775) - TimePicker is not correct in RTL (right-to-left) languages
  - [flutter/55535](https://github.com/flutter/flutter/issues/55535) - New DatePicker widget is not fully  localized
  - [flutter/63373](https://github.com/flutter/flutter/issues/63373) - Double date separators appearing in DatePicker, preventing date selection
  - [flutter/63176](https://github.com/flutter/flutter/issues/63176) -  App.framework path in Podfile incorrect

### [1.20.1](https://github.com/flutter/flutter/pull/62990) (August 6, 2020)
This hotfix release addresses the following issues:
  - [flutter/60215](https://github.com/flutter/flutter/issues/60215) - Creating an Android-only plug-in creates a no-op iOS folder.

### 1.20.0 (August 5, 2020)
Initial stable release.

## Flutter 1.17 Changes
### [1.17.5](https://github.com/flutter/flutter/pull/60611) (June 30, 2020)
This hotfix release addresses the following issues:
  - [flutter-intellij/4642]https://github.com/flutter/flutter-intellij/issues/4642  - Intellij/Android Studio plugins fail to show connected Android devices.

### [1.17.4](https://github.com/flutter/flutter/pull/59695) (June 18, 2020)
This hotfix release addresses the following issues:
  - [flutter/56826](https://github.com/flutter/flutter/issues/56826)  - xcdevice polling may use all free hard drive space

### [1.17.3](https://github.com/flutter/flutter/pull/58646) (June 4, 2020)
This hotfix release addresses the following issues:
 - [flutter/54420](https://github.com/flutter/flutter/issues/54420)  - Exhausted heap space can cause machine to freeze

### [1.17.2](https://github.com/flutter/flutter/pull/58050) (May 28, 2020)
This hotfix release addresses the following issues:
 - [flutter/57326](https://github.com/flutter/flutter/issues/57326)  - CupertinoSegmentedControl does not always respond to selections
 - [flutter/56898](https://github.com/flutter/flutter/issues/56898) - DropdownButtonFormField is not re-rendered after value is changed programmatically
 - [flutter/56853](https://github.com/flutter/flutter/issues/56853) - Incorrect git error may be presented when flutter upgrade fails
 - [flutter/55552](https://github.com/flutter/flutter/issues/55552) - Hot reload may fail after a hot restart
 - [flutter/56507](https://github.com/flutter/flutter/issues/56507) - iOS builds may fail with “The path does not exist” error message

### [1.17.1](https://github.com/flutter/flutter/pull/57052) (May 13, 2020)
This hotfix release addresses the following issues:
 - [flutter/26345](https://github.com/flutter/flutter/issues/26345) - Updating `AndroidView` layer tree causes crash on Xiaomi and Moto devices
 - [flutter/56567](https://github.com/flutter/flutter/issues/56567) - Xcode legacy build system causes build failures on iOS
 - [flutter/56473](https://github.com/flutter/flutter/issues/56473) - Build `--tree-shake-icons` build option crashes computer
 - [flutter/56688](https://github.com/flutter/flutter/issues/56688) - Regression in `Navigator.pushAndRemoveUntil`
 - [flutter/56479](https://github.com/flutter/flutter/issues/56479) - Crash while getting static type context for signature shaking

### 1.17.0 (May 5, 2020)
Initial stable release.

## Flutter 1.12 Changes
### Hotfix.9 (April 1, 2020)
This hotfix release addresses the following issues:
 - [flutter/47819](https://github.com/flutter/flutter/issues/47819) - Crashes on ARMv8 Android devices
 - [flutter/49185](https://github.com/flutter/flutter/issues/49185) - Issues using Flutter 1.12 with Linux 5.5
 - [flutter/51712](https://github.com/flutter/flutter/issues/51712) - fixes for licensing from Android sdkmanager tool not being found

### [Hotfix.8](https://github.com/flutter/flutter/pull/50591) (February 11, 2020)
This hotfix release addresses the following issues:
 - [flutter/50066](https://github.com/flutter/flutter/issues/50066) - binaries unsigned in last hotfix
 - [flutter/49787](https://github.com/flutter/flutter/issues/49787) - in a previous hotfix, we inadvertently broke Xcode 10 support. Reverting this change would have caused other problems (and users would still have to upgrade their Xcode with the next stable release), we decided to increase our minimum supported Xcode version. Please see the linked issue for more context on this decision.
 - [flutter/45732](https://github.com/flutter/flutter/issues/45732) - Android log reader fix
 - [flutter/47609](https://github.com/flutter/flutter/issues/47609) - Android log reader fix

### [Hotfix.7](https://github.com/flutter/flutter/pull/49437) (January 26, 2020)
This hotfix release addresses the following issues:
- [flutter/47164](https://github.com/flutter/flutter/issues/47164) - blackscreen / crash on certain Huawei devices
- [flutter/47804](https://github.com/flutter/flutter/issues/47804) - Flutter engine crashes on some Android devices due to "Failed to setup Skia Gr context"
- [flutter/46172](https://github.com/flutter/flutter/issues/46172) - reportFullyDrawn causes crash on Android KitKat

### Hotfix.5 (December 11, 2019)
Initial stable release.
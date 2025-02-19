<h1 align="center"> MonitorControl </h1>

<!-- subtext -->
<div align="center">
Control your external monitor brightness, contrast or volume directly from a menulet or with keyboard native keys.
</div>

<br/>

<!-- Language emoji -->
<div align="center">
    <p>Translations: 🇨🇳 :uk: :fr: :de: :it: :ru: 🇺🇦 </p>
</div>

<br/><br/>

<div align="center">
    <img src="./.github/menulet.png"  alt="menulet screenshot"/>
    <br/><br/>
    <img src="./.github/menugeneral.png" width="400" alt="general screenshot"/><img src="./.github/menukeys.png" width="400" alt="keys screenshot"/>
    <br/><br/>
    <img src="./.github/menudisplay.png" width="400" alt="display screenshot"/><img src="./.github/menuadvanced.png" width="400" alt="advanced screenshot"/>

<br/>

*Bonus: Using keyboard keys displays the native osd*

<img src="./.github/osd.jpg" width="500" align="center" alt="osd screenshot"/>
</div>

## Download

Go to [Release](https://github.com/monoKeith/MonitorControl/releases) and download the latest `.zip`


## How to help

This repo was forked from the [original](https://github.com/the0neyouseek/MonitorControl) repo, open [issues](https://github.com/the0neyouseek/MonitorControl/issues) if you have a question, an enhancement to suggest or a bug you've found. If you want you can fork the code yourself and submit a pull request to improve the app.

## How to build

### Required

- Xcode
- [Carthage](https://github.com/Carthage/Carthage)
- [Swiftlint](https://github.com/realm/SwiftLint)
- [SwiftFormat](https://github.com/nicklockwood/SwiftFormat)

Clone the project
```sh
$ git clone https://github.com/monoKeith/MonitorControl.git
```
Then download the dependencies with Carthage
```sh
$ carthage bootstrap --platform macOS
```

You're all set ! Now open the `MonitorControl.xcodeproj` with Xcode

### Third party dependencies

- [MediaKeyTap](https://github.com/the0neyouseek/MediaKeyTap)
- [MASPreferences](https://github.com/shpakovski/MASPreferences)
- [DDC.swift](https://github.com/reitermarkus/DDC.swift)
- [AMCoreAudio](https://github.com/rnine/AMCoreAudio)

## Support
- macOS Catalina (`10.15`) and up.
- Works with monitors controllable via [DDC](https://en.wikipedia.org/wiki/Display_Data_Channel).

## Contributors & Thanks
- [@the0neyouseek](https://github.com/the0neyouseek)
- [@reitermarkus](https://github.com/reitermarkus)
- [@JoniVR](https://github.com/JoniVR)
- [@bluejamesbond](https://github.com/bluejamesbond/) (Original developer)
- [@Tyilo](https://github.com/Tyilo/) (Fork)
- [@Bensge](https://github.com/Bensge/) - (Used some code from his project [NativeDisplayBrightness](https://github.com/Bensge/NativeDisplayBrightness))
- [@nhurden](https://github.com/nhurden/) (For the original MediaKeyTap)
- [@kfix](https://github.com/kfix/ddcctl) (For ddcctl)

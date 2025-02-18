[![GitHub top language](https://img.shields.io/github/languages/top/FredHappyface/Android.FHCode.svg?style=for-the-badge)](../../)
[![Repository size](https://img.shields.io/github/repo-size/FredHappyface/Android.FHCode.svg?style=for-the-badge)](../../)
[![Issues](https://img.shields.io/github/issues/FredHappyface/Android.FHCode.svg?style=for-the-badge)](../../issues)
[![License](https://img.shields.io/github/license/FredHappyface/Android.FHCode.svg?style=for-the-badge)](/LICENSE.md)
[![Commit activity](https://img.shields.io/github/commit-activity/m/FredHappyface/Android.FHCode.svg?style=for-the-badge)](../../commits/master)
[![Last commit](https://img.shields.io/github/last-commit/FredHappyface/Android.FHCode.svg?style=for-the-badge)](../../commits/master)
[![GitHub all releases](https://img.shields.io/github/downloads/FredHappyface/Android.FHCode/total?style=for-the-badge)](../../releases)

<!-- omit in toc -->
# Android.FHCode

<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">

Code editor for android

- [Features](#features)
- [Screenshots](#screenshots)
- [Documentation](#documentation)
- [Gradle tasks](#gradle-tasks)
- [Language Information](#language-information)
	- [Kotlin and Android Version](#kotlin-and-android-version)
		- [Download Android Studio](#download-android-studio)
- [How to Run](#how-to-run)
	- [Build From Source](#build-from-source)
	- [Get it on F-Droid](#get-it-on-f-droid)
	- [Get it on Google Play](#get-it-on-google-play)
	- [Download the APK](#download-the-apk)
- [Download Project](#download-project)
	- [Clone](#clone)
		- [Using The Command Line](#using-the-command-line)
		- [Using GitHub Desktop](#using-github-desktop)
	- [Download Zip File](#download-zip-file)
- [Community Files](#community-files)
	- [Licence](#licence)
	- [Changelog](#changelog)
	- [Code of Conduct](#code-of-conduct)
	- [Contributing](#contributing)
	- [Security](#security)
	- [Support](#support)
	- [Rationale](#rationale)

## Features

- Create, edit and save code/ text files
- Syntax highlighting for Java, XML, Python using regex
- 4 Themes: Light, Dark, Black, Auto
- Configurable text size
- Launcher Shortcuts for Settings, About, New File

## Screenshots

<p>
<img src="metadata/en-US/images/phoneScreenshots/screenshot-1.png" alt="Screenshot 1" width="300">
<img src="metadata/en-US/images/phoneScreenshots/screenshot-2.png" alt="Screenshot 2" width="300">
<img src="metadata/en-US/images/phoneScreenshots/screenshot-3.png" alt="Screenshot 3" width="300">
<img src="metadata/en-US/images/phoneScreenshots/screenshot-4.png" alt="Screenshot 4" width="300">
<img src="metadata/en-US/images/phoneScreenshots/screenshot-5.png" alt="Screenshot 5" width="300">
<img src="metadata/en-US/images/phoneScreenshots/screenshot-6.png" alt="Screenshot 6" width="300">
</p>

## Documentation

A high-level overview of how the documentation is organized organized will help you know
where to look for certain things:

<!--
- [Tutorials](/documentation/tutorials) take you by the hand through a series of steps to get
  started using the software. Start here if you’re new.
-->
- The [Technical Reference](/documentation/reference) documents APIs and other aspects of the
  machinery. This documentation describes how to use the classes and functions at a lower level
  and assume that you have a good high-level understanding of the software.
<!--
- The [Help](/documentation/help) guide provides a starting point and outlines common issues that you
  may have.
-->

## Gradle tasks

- ktlintCheck (`gradlew ktlintCheck`): run ktlint over the codebase
- genDocs (`gradlew genDocs`): generate the api reference using dokka

## Language Information

### Kotlin and Android Version

This app has been written in Kotlin 1.5.0 with the Android Studio IDE.

- The target SDK version is 31 (Android 12)
- The minimum SDK version is 26 (Android 8 Oreo)

#### Download Android Studio

Download the Android Studio IDE from <https://developer.android.com/studio/>.
For Windows, double click the downloaded .exe file and follow the instructions
provided by the installer - it will download the Android emulator and the
Android SDK. Additional information can be found at
<https://developer.android.com/studio/install>

## How to Run

### Build From Source

1. Download or clone this GitHub repository
2. (If downloaded) Extract the zip archive
3. In Android Studio click File > Open and then navigate to the project file
(Android studio defaults to the directory of the last opened file)

### Get it on F-Droid

1. Open the F-Droid app
2. Search for FHCode

or

[<img src="readme-assets/badges/f-droid-download.png"
alt="Get it on F-Droid" height="80">](https://f-droid.org/en/packages/com.fredhappyface.fhcode/)

Follow the link to the listing on F-Droid by clicking on the badge above,
then download/ install

### Get it on Google Play

1. Open the Google Play app
2. Search for FHCode

or

[<img src="readme-assets/badges/google-play-download.png"
alt="Get it on Google Play" height="80">](https://play.google.com/store/apps/details?id=com.fredhappyface.fhcode)

Follow the link to the listing on Google Play by clicking on the badge above,
then download/ install

### Download the APK

1. For releases, navigate to the /app/release directory. For debug, navigate to /app/debug
2. Select the debug or release APK depending on your preference. Note that the
filenames are in the form: com.fredhappyface.fhcode-(version)-(debug|release).apk

or

[<img src="readme-assets/badges/direct-apk-download.png" alt="Direct apk
download" height="80">](/app/release)

Follow the link to the /app/release directory by clicking on the badge above.

## Download Project

### Clone

#### Using The Command Line

1. Press the Clone or download button in the top right
2. Copy the URL (link)
3. Open the command line and change directory to where you wish to
clone to
4. Type 'git clone' followed by URL in step 2

	```bash
	git clone https://github.com/FredHappyface/Android.FHCode
	```

More information can be found at
https://help.github.com/en/articles/cloning-a-repository

#### Using GitHub Desktop

1. Press the Clone or download button in the top right
2. Click open in desktop
3. Choose the path for where you want and click Clone

More information can be found at
https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop

### Download Zip File

1. Download this GitHub repository
2. Extract the zip archive
3. Copy/ move to the desired location

## Community Files

### Licence

MIT License
(See the [LICENSE](/LICENSE.md) for more information.)

### Changelog

See the [Changelog](/CHANGELOG.md) for more information.

### Code of Conduct

Online communities include people from many backgrounds. The *Project*
contributors are committed to providing a friendly, safe and welcoming
environment for all. Please see the
[Code of Conduct](https://github.com/FredHappyface/.github/blob/master/CODE_OF_CONDUCT.md)
 for more information.

### Contributing

Contributions are welcome, please see the
[Contributing Guidelines](https://github.com/FredHappyface/.github/blob/master/CONTRIBUTING.md)
for more information.

### Security

Thank you for improving the security of the project, please see the
[Security Policy](https://github.com/FredHappyface/.github/blob/master/SECURITY.md)
for more information.

### Support

Thank you for using this project, I hope it is of use to you. Please be aware that
those involved with the project often do so for fun along with other commitments
(such as work, family, etc). Please see the
[Support Policy](https://github.com/FredHappyface/.github/blob/master/SUPPORT.md)
for more information.

### Rationale

The rationale acts as a guide to various processes regarding projects such as
the versioning scheme and the programming styles used. Please see the
[Rationale](https://github.com/FredHappyface/.github/blob/master/RATIONALE.md)
for more information.

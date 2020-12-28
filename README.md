## EVA
[![Build Status](https://travis-ci.org/wallabag/ios-app.svg?branch=master)](https://travis-ci.org/wallabag/ios-app) ![](https://img.shields.io/badge/Updated-December%2029,%202020-lightgrey.svg)
> something

Join EVA beta

<table width="100%">
	<tr>
	<td width="50%" align='center'>
EVA cares about your recycling for you! 🌱 <br><br>
Home recycling collection service with real-time tracking and traceability. Plus awards system, statistics and education menu. <br>
Classify your waste and contribute to the conservation of the environment! 🌎
	</td>
	<td width="80%" align='center'>
<img height="60%" src=https://raw.githubusercontent.com/CxrlosKenobi/EVA-app/main/assets/logo.png>
	</td>
	<table>

## Prototype  

## Features
- [x] Feature 1
- [x] Feature 2
- [x] Feature 3

## Contributing
- Report bugs and make suggestions
- Write some code. Please follow the code style to make a review process later.

## Version Management

* Build Number willl increased for each iTunes submission
* App version will only increase on app submiting to App Store
* Each version will have build no starting from 1000

## Folder Structure and Architecture

- Each `Module` Will have its own folder. eg -
	- Splash
	- Onboarding
	- Profile
- Constants, Generic View, Data Model, Helper etc each will have its own folder
- `SupportingFiles` folder will have
	- Bridging-Header.h
	- Frameworks (Folder for 3rd paty code which does not have Cocoapods)
	- AppDelegate.swift
	- LaunchScreen.storyboard
	- Info.plist

## Git

- `dev` will be the semi-stable branch with `tag` on each stable merge. This is the branch from where IPA should be published to iTunes Test Flight
- `master` will have code that are fully stable with `release` on each merge. App store publishing should be done from this branch only.
- Each branch should start with two or three letter Project Name, MileStone
 `<Project-Name>-<Mile-Stone>-<Module-Name>`
	-  BG-M5-Login
- Git commit should have multiline comments, where first line comment should start with tag like
	- [FIXED]
	- [ADDED]
	- [UPDATED]
	- [TEST]

## Requirements
- iOS 10+
- XCode 8.2.1
- Swift 3.0.2


## License



## Go to <a href="https://appeva.co" target="_blank">AppEva.co</a> !

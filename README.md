***
# **Mobile based Virtual-Traffic-Lights System UI and UX Design**
![slogan](https://github.com/MasonNZ666/Virtual-Traffic-Lights/raw/main/slogan.png)
***

## Introduction
`Traffic Control` `Mobile Based` `UI` `UX`

The virtual traffic light system is a mobile application which aims to replace the traditional traffic lights, analyze the vehicle conditions at intersections in real-time through the cloud and know that they pass in order. The system provides users with navigation information and intersection traffic status during their driving, improves traffic efficiency at intersections, and improves traffic congestion and safety.

## Features
* Virtual Traffic Lights provide the following features:
* Locate user location
* Browse maps
* Set destination and plan arrival route
* Calculate arrival time
* Quick navigation to favourite places
* Indicate the driver's signal light status when passing the intersection
* Calculation of vehicle passing sequence by the algorithm
* CarPlay Sync

## Getting Start
* You can preview the application's UI and UX immediately through the [sharing link of Figma](https://www.figma.com/file/Q2JLfDiACU50CTlNoviOND/COMP826-Assessment-2?node-id=0%3A1).
* Interact with the UI through "Present" simulate application running scenarios.
* Provide the export of multi-format pictures and CSS, iOS, and Android style code for cross-platform development.

### Usage
![usage](https://github.com/MasonNZ666/Virtual-Traffic-Lights/raw/main/Usage.gif)

## Development Environment
The VTL system will be developed using React Native. The following table lists the relevant technologies and development tools required.
* Development platform: macOS
* Target platforms: Android, IOS
* Operating environment: JSCore
* Operation dependency: Node, JDK, Watchman
* Programing language: JavaScript, Python
* SDK: React Native
* IDE: VS Code, Android Studio, XCode
* IOS virtual machine: CocoaPods
* AVD Manager: Android Studio
* Database: SQLite
* UI and UX design: Figma

## Implementation
When the application is started, the mobile device uploads the GPS information to the server. The server matches it with the database and transmits the matched map to the mobile device. The location information is uploaded to the server when the user closes an intersection. If the server detects that there are other vehicles nearby and there is a passing conflict, it executes the corresponding algorithm and broadcasts the calculation results to the area to make the vehicles in the area pass in order.

![](https://github.com/MasonNZ666/Virtual-Traffic-Lights/raw/main/Overview.png)

## Contributing
Thank you for your valuable time! The contribution makes the open-source community an excellent place for inspiration and creation. Any contribution you make will benefit many people. Please try creating the following error report:
* Steps to reproduce the problem.
* As many specific details as possible.

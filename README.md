# StormyRefactored

In this project, the main objective was to refactor an existent Android app with the following conditions:
* Change the existing activites to Fragments
* The app needs to handle rotation without restarting the app
* The background gradient changes colour depending on the current temperature.

The following features were also added:
* The use of Shared Preferences to store data regarding the last known location and temperature, in case there is some problem with the user's GPS.
* The app now tries to update the weather location based on the user location.
  * In order to do that, Permissions have been added, in accordance with Android API 23
* Different layouts were added to accomodate the tablet, with the use of viewpagers.
* Interfaces were added to communicate information between fragments
* A different layout for the Landscape mode in the phones was added, to enhance the user experience.

## Tablet Layouts

![Tablet Layout 1](https://raw.githubusercontent.com/Vanethos/StormyRefactored/ReadmeChange/Stormy/Tablet_1.png)
![Tablet Layout 2](https://raw.githubusercontent.com/Vanethos/StormyRefactored/ReadmeChange/Stormy/Tablet_2.png)

## Added Phone Layouts

![Phone Landscape](https://raw.githubusercontent.com/Vanethos/StormyRefactored/ReadmeChange/Stormy/Phone%204.png "Phone Landscape")

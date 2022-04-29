# VMeasure
### Measurement app in AR for Oculus devices

Use your Oculus Quest 2 with Passthrough as a tape measure.

## Demos

<img src="Demos/demo.gif" />

NB: This demo is recorded using the sharing app of Oculus. So, we can see only a black background instead of real background. But the app will show the real camera feed while running it in the Oculus device. 

## Requirements

- Unity3D
- Oculus Quest 2 (system version 35)

## How to install?

- Follow [these instructions](https://sidequestvr.com/setup-howto) to install SideQuest and setup your Oculus Quest 2 for development.

- [Download the latest APK](https://github.com/codemaker2015/oculus-measure-app/Builds/vmeasure.apk).

- Connect your Oculus Quest to your computer, launch SideQuest and drag the APK to the top left corner of SideQuest to install it.

- Or use `adb install vmeasure.apk` in the command prompt on the folder where the apk is located. 

## How to use it?

- On your Quest 2: open "Apps", select "Unknown Sources" on the drop-down menu on the top right corner, and then select "Measure".

- Press the trigger button to start measuring, and then press it a second time to stop measuring or press "B" (on the right controller) to cancel this measurement.

- Press "B" (on the right controller) to clear all measurements.

## How to build?

- Make sure you have Unity 2020.3 LTS installed (with Android Build support).

- Clone this project.

- Open the project with Unity, then open the Package Manager, and import the Oculus Integration package (version 35.0).

- Navigate to **File > Build Settings...**, select the **Android** platform, then select your Oculus Quest as the **Run device** (if it's plugged in) and then click on **Build and Run**.

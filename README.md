## How to use the app
1. Clone the repo, open it in Android Studio, and press Run to launch on an emulator or device.
2. Clicking the button will either show or hide the badge.
   
## Explanation
App demonstrates how to use a Box layout in Jetpack Compase to overlay a notification badge on a profile picture.
- A circular profile picture placeholder is created using a `Box` with `CircleShape` and background color.
- A notification badge (small green circle with a number) is aligned to the bottom-end corner of the profile picture using `Modifier.align()`.
- A toggle button allows the user to show or hide the badge.

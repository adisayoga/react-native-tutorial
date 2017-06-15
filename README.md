
# Getting Started

Assuming that you have Node installed, you can use npm to install the 
`create-react-native-app` command line utility:

    $ npm install -g create-react-native-app

Then run the following commands to create a new React Native project called 
"react-native-tutorial":

    $ create-react-native-app react-native-tutorial
    
## Running your app on a virtual device

  * Install the [Expo](https://expo.io/) in your development machine
  * Run Expo XDE and open this project
  * Click "Device" on Expo XDE and then "Open on Android (Crtl + D)".<br>
    **Note**: Make sure your virtual device is already running or Expo will throw
    an error: No android device found
  * If everything works, you should see starter app on your virtual device.

<p align="center">
  <img src="https://user-images.githubusercontent.com/407778/27115649-aebf991a-50fe-11e7-8b7c-c9fd64b967e2.png" width="250">
</p>

**Tips running android virtual device without Android Studio:**

Assuming you already created virtual device on Android studio, run this command 
(windows):

    $ cd %ANDROID_HOME%\tools
    $ emulator -avd <avdName>

You can get the names of the emulator from the list:

    $ bin\avdmanager list avd

-----------

This repository contains several branches based on the tutorial:

  1. `props`
  2. `state`
  3. `style`
  4. `dimensions`
  5. `layout`
  5. `text_input`
  6. `touch`
  7. `scroll`
  8. `listview`

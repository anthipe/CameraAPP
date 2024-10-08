# CameraAPP
An android app that opens the camera by moving the device.

## DESCRIPTION
The aim of this project was to create an Android app that opens the camera of your mobile phone. Specifically, it uses the **accelerometer** of the device to achieve _this goal_. When the user opens the app, they see a message and a button below that. When the user presses the button, they will get a **pop-up warning message** asking them for **permission** to open the camera. In case they agree and press the "Ok" button, they will have to _shake_ the Android device in order for the camera to open up and take a picture. 
>For users that don't have an Android device, the steps to achieve this are shown below in the emulator section.

## WHAT IS AN ACCELEROMETER USED FOR?
Accelerometers measure acceleration, which in practical terms means changes in speed or direction.

## FILES
Begin by **downloading the .zip file and extracting all the contents**. After the download open the file contents on _AndroidStudio _ IDE.
There are two main files in the zip . The first one is the main activity which contains the code for the camera permission and the listeners. The second one contains the code for the accelerometer 

In order to see the source code open the folder ***app*** then ***src*** and ***main,java,com,example,mycamera***

## CODE
For this project, 

-XML was used to make the UI 

-Java was used for the source code

## PAGES 
This is the _main_ page of the app

![Screenshot of the main page](sceenshots/main.png)

This is the _consent_ page 

![Screenshot of the consent page](sceenshots/consent.png)

This is the _accelerometer_ page 

**if you don't own an android device** you can use the **extended controls** of the IDE by **clicking** the 3 dots above the emulator and then by **clicking virtual sensors** you can move and rotate the device 


![Screenshot of the accelerometer  page](sceenshots/accelerometor.png)

This is the _final_ page 

![Screenshot of the final page](sceenshots/final.png)

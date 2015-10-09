# xPico Wi-Fi Camera using the SDK

## Summary
This is a module for the xPico Wi-Fi which interfaces with a VC0706 camera module from Adafruit. You can find the camera here: http://www.adafruit.com/product/397

## How to video
[http://img.youtube.com/vi/qcIX7abym-8/0.jpg)](http://www.youtube.com/watch?v=qcIX7abym-8)

## How to use
Put this source code in your c:\xpicowifi\custom\module\vc0706 directory. Create a project in c:\xpicowifi\custom\project that has vc0706 as one of the modules in the modules.make file. Build the project per the SDK instructions, and flash the firmware into an xPico Wi-Fi.

Connect a VC0706 camera to the TX and RX pins of Line 1 in the xPico Wi-Fi, plus power and ground. Point your browser to <xpico wifi ip address>/embedded/vc0706/http/camera.html and you will see the camera.
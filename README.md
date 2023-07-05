# Virtual-Glasses

Implementation of virtual glasses using Three.js + TensorFlow.js Facemesh model. 

Experience the cutting-edge fusion of computer vision and augmented reality

Allowing users to try on various 3D glasses in real-time.

## Installing
Clone this repository to your local computer
``` bash
git https://github.com/bensonruan/Virtual-Glasses.git
```
Install three.js
``` bash
npm install --save three
```
Point your localhost to the cloned root directory

Browse to http://localhost/index.html 

## Face Keypoints 
The facemesh detected keypoints that used for overlay the 3D Glasses:
* Middle between Eyes : 168
* Left Eye : 143
* Bottom of Nose : 2
* Right Eye : 372

## Put Mask On
* Click "Try it On" to turn on the Webcam switch, and allowing the browser to access your webcam 
* Wait for a few seconds to Load Model for face landmark detection
* Choose the 3d glasses you would like to try on, watch yourself in fashion

## Notes
* Please note that on IOS Safari, cameras can only be accessed via the https protocol 
* Facemesh model is designed for front-facing cameras on mobile devices, where faces in view tend to occupy a relatively large fraction of the canvas. MediaPipe Facemesh may struggle to identify far-away faces.

## Library
* [jquery](https://code.jquery.com/jquery-3.3.1.min.js) - JQuery
* [webcam-easy.js](https://github.com/bensonruan/webcam-easy) - javascript library for accessing webcam stream and taking photos
* [facemesh](https://github.com/tensorflow/tfjs-models/tree/master/facemesh) - MediaPipe Facemesh is a lightweight machine learning pipeline predicting 486 3D facial landmarks to infer the approximate surface geometry of a human face

## Credit 3D glasses models
* [Sport Glasses B307](https://sketchfab.com/3d-models/sport-glasses-b307-7630c4ac090c42598de43d47554b4cf4
) by	hanchiahui
* [Glasses 07](https://sketchfab.com/3d-models/glasses-07-06b22104f56a4356aa9ffa825abd8d6b) by	Dokono Kinokoda
* [Cartoon Glasses](https://sketchfab.com/3d-models/cartoon-glasses-fddd63a49615405fb17f5c7ff65345c2) by	Lucas_Bartolomeo
* [Plastic Sunglasses](https://sketchfab.com/3d-models/plastic-sunglasses-d5417dcb97fb41b39f57fc8772a7ecab) by	Incg5764
* [Aviator sunglasses](https://sketchfab.com/3d-models/aviator-sunglasses-00d1cb5aa82745228a3b764c97f867de
) by	Kimppo
* [EyeGlasses](https://sketchfab.com/3d-models/eyeglasses-8ec54755399a4eca8a1356812e68fe02) by	thelegendofwolf
* [3D frames generated in less than 10 seconds](https://sketchfab.com/3d-models/3d-frames-generated-in-less-than-10-seconds-5cc3b37589ba43148352c850a764b2db
) by	VReeAI

## Support me 
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W6METMY)

# Bike Alert
This project was inspired by a love for cycling and a realization of the many distractions cyclists face. Cyclists are often distracted by advertisements and commotion on the road, and to pedestrians, a distracted cyclist can be a serious hazard. Thousands of pedestrians are injured by cyclists in major US cities every year. Until cities build and maintain proper cycling infrastructure, pedestrians will continue to fall victim to distracted cyclists. This is where our project comes in.

Overview
-----
Bike Alert is a pedestrian alerting system that uses computer vision to automatically warn pedestrians of cyclists. This way, if cyclists are distracted, pedestrians will still be alerted of their presence. The device houses a camera and a distance sensor connected to a Raspberry Pi running a program that performs real-time human detection to sound a speaker whenever a person is detected within a few meters. The system is housed inside a custom 3D printed case that is mounted on a cyclist's handlebars.

This program is heavily based on EdjeElectronic's [TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi](https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/blob/master/Raspberry_Pi_Guide.md) guide.

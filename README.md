# diyrov
I'm currently working on a rov using a 3" tubes with 3d printed parts for thrusters, housings, etc.
The entire design is open-source, so feel free to build one yourself. Be aware that it is not finished yet and I'm not sure wether it works or not :P

## parts
- Raspberry Pi 3
- Arduino Uno
- Raspberry Pi Camera
- 3x 30A Car ESCs (link comes soon)
- 3x Turnigy Brushless Motors
- 3D printer
- Laptop with a old XBOX 360 controller
- Network Tether (50m)
- 3" tube from bluerobotics
- voltage sensors (link comes soon)
- gyro (link comes soon)

## software
- node.js application running on the raspberry pi which communicates with the arduino and provides a realtime interface with websockets
- arduino sketch to control the escs, gyro, voltage sensor
- electron client application which wraps the website in a "hud"-way (work in progress)
- gstreamer server and client over udp for the live-feed


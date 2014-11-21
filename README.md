MyQuadCopter-
=============

A Tilt QuadCopter with wings and wheels


In this repository I will write my thoughts, sketches and code about a Drone that I have in mind.

This QuadCopter isn't a usual one. This QuadCopter have the following features:

1. It has 4 wheels and 4 motors connected to them in order to move on the road.
2. It has 4 motors with propellers in an H positioning.
3. Each motor can tilt (in one axis).
4. It has wings in order to fly as an Airplane.
5. Each wing is attached to a servo in order to close when in ground and open when in the Air.
6. Each wing has an Aileron controlled by a servo (Roll Axis).
7. A vertical stabilizer on the back of the body.
8. A rudder attached to the vertical stabilizer controlled with a servo (Yaw Axis).
9. A horizontal stabilizer left and right of the vertical stabilizer.
10. An elevator attached to the horizontal stabilizer controlled by a servo (Pitch Axis).
11. All the servos are connected to an Arduino (Atmel microcontroller).
12. The Arduino is connected to a Raspberry Pi over Serial.
13. A 3g USB Module is connected to the Raspberry Pi to provide Internet communication.
14. The Raspberry Pi Handles all the calculations and functions. The Arduino is used to help Rpi communicate with the servos and motors.
15. A web server running on the Raspberry Pi + the 3g connection allow us to remotely control our Rpi and sends commands to it.
16. Several Cameras are attached to the body; connected to the Rpi through USB.
17. Cameras record video of the operation in a usb stick connected to Rpi.
18. Video output of Cameras is sent to the client on demand (if the client asks for it) through the web server (running on the Rpi).
19. A Gyroscope + Accelerometer is attached the body connected to the Rpi. The Rpi Handles the stabilization of the Drone. The Data are being saved with time stamps for latter research. Data are being sent to the clien through the web server.
20. An altitude sensor (BMP085) connected to the Arduino. Data are being sent to the clien through the web server.
21. A GPS module connected to the Arduino. Data are being sent to the clien through the web server.

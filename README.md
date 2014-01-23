UWU_Bot
=======

Kinect 3D Mapping Robot with ROS & Arduino

////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////

This is temporary build package for Arduino and ROS controlled localization and Mapping Robot..

Need:

  Arduino pro mini or compatible
  Dual H Bridge high power MOSFET motor driver
  Microsoft X box 360 Kinect sensor
  Mobile robot with differential drive
  

How to do:

Download .zip and unzip to a didectory called YourPath/uwu_bot
give permissions to all .sh files and uwu_bot file "chmod +x Yourpath/File"
Upload the provided sketch to an arduino pro mini or compatible
Make sure the arduino serial port set to ttyUSB0
Then in a new shell run this YourPath/uwu_bot/uwu_bot
It will open new shell and runs

  roscore
  serial node
  uwu_bot node
  openni launch
  ccny tools launch
  rviz vissualization
  mapping starts here
  

This is the way the project works. Follow instructions and if you have issues, report them here.
Do not use serail monitor in arduino IDE, it will disconnect the serial node and the robot as well.
No "Serial.print()" commands in arduino sketch.


Final year research project of Mechatronics, Uva Wellassa University of Sri Lanka

///////////////////////////////////////////////////////////////////////////////
///////////////////////////////////////////////////////////////////////////////

# The Doowybot
A 3D printable sub $100 robot

### About
The Doowybot was designed initially as a platform for the IEEE Ottawa 
Robotics Competition Arduino Challenge. [More Info]

The Doowybot is being released publicly with the hopes that it allows
anyone interested in robotics to get started with a platform that doesn't 
cost a fortune and is easy to use.

All of the electronic parts have been sourced from [RobotShop]. The chassis can be completely 3D printed accept for 6 4-40x1/4"
screws that hold the chassis together. These can be found in hardware stores, hobby stores, and most electronics stores. Ebay
has about a million as well.

The Doowybot is based on the arduino platform, being centred around an Arduino Uno.
A motor controller shield is used to drive the Doowybot's two gear motors. We've chosen
to use two reflectance sensors (QTR-1A) and one sonar sensor (HC-SR05). These sensors
were chosen based on their usability, availability and support. Both sensors can be used
easy with the Arduino uno and can be used for applications such as collision avoidance and
line following. 

### Getting Started
To get your Doowybot up and running follow the Building instructions in the doc
directoy.
An instructable is in the works as well to make it even easier to make a Doowybot.
The really quick high level instructions are:

1. Source all of your parts. This means 3d print the chassis and buy everything listed in the BOM.
2. Put the mechanical chassis together, make sure everything fits together as expected. If not, repeat step 1.
3. Connect all of the electronics according to the schematic in the doc directory.
4. Load the sample program to test the Doowybot's functionality.

### Example
A sample program will be provided in the example directory. Use this to test your Doowybot's basic functionality

### Special Thanks
A really big thanks goes out to a few certain people:
* Jeff Dai for being a huge help in the mechanical design of the chassis
* Alok Deshpande for getting all of the electronics to play nicely together
* All of the IEEE ORC people that supported the arduino platform idea

### Roadmap
* [ROS] integration with Gazebo simulation
* Adding support for new sensors
* Porting to a Raspberry Pi for a more powerful, but expensive, version of the Doowybot

[More Info]:http://www.orc.ieeeottawa.ca/home/
[RobotShop]:http://www.robotshop.com/
[ROS]:http://www.ros.org/

# OpenCR board code

Modified OpenCR board code to use a color sensor on a Turtlebot3 Burger.
The sensor must be connected to the SCL and SDA ports of the board.


# Published topics
* ```/colorSensorValue``` ([std_msgs/Int16MultiArray]) 

Array of the values (R,G,B) measured by the color sensor.


## Use It
Clone the OpenCr board code:
```
git clone https://github.com/ROBOTIS-GIT/OpenCR.git
```

Replace the folder turtlebot3_core by this one in the openCR code: 
```
arduino/opencr_arduino/opencr/libraries/turtlebot3/examples/turtlebot3_burger/
```

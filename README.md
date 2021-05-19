# Robotics Systems
This is a coursework assignment for unit EMATM0053 Robotic Systems at University of Bristol. 

## Overview
The assignment implements a mobility stop experiment, utilising the VL6180X (https://www.st.com/resource/en/datasheet/vl6180x.pdf) sensor's 
Ambient Light Sensor (ALS) module to calculate the distance between itself and a light source. 

## Contributions To Literature
This project contributes to relevant literature since it is the first implementation that uses the ALS module to calculate distance through
the _Light-based Inverse Square Law_ within a Robotics context. 


## Implementation Procedure

### Arduino Code
* Run and compile the Romi.ino file on Romi mobile robot to verify there are no errors
* Press the 'on/off' button to verify that Romi works as directed in the report
* Turn on serial monitor to verify if data is being outputted

### To read data from the serial monitor:
* Connect the Romi to a computer, and check that the required data is correctly outputted to the screen
* Make sure that the Arduino serial monitor is closed
* To make the python script start listening to the serial port, run:
```
python read_serial_data.py
```
The program will time out after 180seconds. The data will be saved in the csv file called serial_data.csv.



For more information, contact me through my e-mail **sanyam_vyas@hotmail.com**


# M3X-project
The repository contains all the files and information needed to stream data from the MyoPro arm robot. 

# Initial hardware and software setup for the robot
There is two way to stream data from the MyoPro arm device:

1- Serial cable:
To collect data from MyoPro using a serial cable, we need to connect the serial cable to one of the USB ports on the PC and find the corresponding port number using a serial streaming app(like Tera Term).

2- Bluetooth:
To stream data via Bluetooth, we need to pair the robot with the PC. Select Start > Settings > Devices > Bluetooth & other devices > Add Bluetooth or other device > Bluetooth. After Pairing the robot, we can find the Bluetooth port using a serial streaming app(like Tera Term).
For the serial port configuration, please visit "M3X Project Interface Document" file. 

In our Python code, we use the port number to collect data using the "serial" module. The port number may change whenever we pair the device with the PC. So, make sure the streaming port number is identified using a serial streaming app(like Tera Term).


# Initial hardware and software setup for the DAQ

First, we need to turn on the DAQ and ensure that the DAQ is paired with the PC. If not, push and hold the button on the DAQ for 5 to 7 seconds until the lights start blinking sequentially. Then find the device  by selecting Start > Settings > Devices > Bluetooth & other devices > Add Bluetooth or other device > Bluetooth and paire it . 
For the data collection from the DAQ, we use the company's Python modules.


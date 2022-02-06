# Drone_Tracking_Pixhwak_Rpi

> Developed a Quadcopter using Pixhawk Mini Flight Controller with Raspberry Pi Model 3b as a companion computer.

> Used the u-blox GPS Module on the drone for better GPS and 3DR Radio Telemetry Module is interfaced with Raspberry Pi which receives the GPS Coordinates of Moving Person.

> Following Figure Shows the Quadcopter that I built for this Autonomous Tracking 

![image](https://user-images.githubusercontent.com/54229744/151697057-287f3f4e-0bcf-4f20-b8bc-469ab97473a0.png)

> I have used Ardupilot Firmware in the Pixhawk Mini Flight Controller.

> For Autonomous control of Flight Controller without Radio Transmitter I used Dronekit python API which sends the high-level commands to the Flight controller through the UART Interface between Raspberry Pi and Pixhawk Mini. It uses the MAVLINK protocol for communication.

![alt text](https://github.com/pranavpeddi1/Drone_Tracking_Pixhwak_Rpi/blob/main/Drone_GPS_Track_ShortGiff.gif)

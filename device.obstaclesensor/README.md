#gb.device.obstaclesensor
Short range infra-red obstacle sensor device.

![Photo](IR Obstacle Sensor - Front.jpg?raw=true "gb.device.obstaclesensor")

##Getting Started on Raspberry Pi:
1. Install gb.device.obstaclesensor and gb.device.gpio from:  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-gpio_0.0.3-1_all.deb  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-obstaclesensor_0.0.3-1_all.deb  
2. Open Gambas
3. Start a new project or open an existing one
4. Goto Menu: Project > Properties > Components > Check/Tick: gb.device.obstaclesensor
5. Write some code...
6. Dim Sensor as New ObstacleSensor(Any Pin BCM Number i.e 17 which is physical pin 11)
7. Print Sensor.IsOn()
![Photo](Test Code Select Component.png?raw=true "gb.device.obstaclesensor")

##Turn Off Raspberry Pi and Do Wiring:
1. Connect Sensor to Male-Female wire connetor
![Photo](IR Obstacle Sensor - Wiring 1.jpg?raw=true "gb.device.obstaclesensor")
2. Connect Wires to Raspiberry Pi
![Photo](IR Obstacle Sensor - Wiring 2.jpg?raw=true "gb.device.obstaclesensor")

###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.obstaclesensor.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.obstaclesensor.Test/.src/FMain.class  

![Photo](Test Code Demo with GPIO Monitor.png?raw=true "gb.device.obstaclesensor")
(The obstacle sensor logic in the GPIO Live Monitor is reversed Off is On and vice versa)

###Also download and try out this live and colourful Pin monitor by Charlie Ogier:  
https://github.com/charlie-ogier/gpio

Thanks  
Matt

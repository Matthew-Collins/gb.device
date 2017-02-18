#gb.device.ultrasonic
Measure distance to obstacles using HC-SRO4.

![Photo](Ultrasonic Front.jpg?raw=true "gb.device.ultrasonic")

##Getting Started on Raspberry Pi:
1. Install gb.device.ultrasonic and gb.device.gpio from:  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-gpio_0.0.3-1_all.deb  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-ultrasonic_0.0.1-1_all.deb  
2. Open Gambas
3. Start a new project or open an existing one
4. Goto Menu: Project > Properties > Components > Check/Tick: gb.device.ultrasonic
5. Write some code...
6. Dim Sensor as New Ultrasonic(Any Pair of BCM Number Pins i.e 17, 18)
7. Print Sensor.GetDistance()
![Photo](Test Code Select Component.png?raw=true "gb.device.ultrasonic")

##Turn Off Raspberry Pi and Do Wiring:
1. Connect Sensor to Female-Female wire connetor
![Photo](Ultrasonic Wiring 1.jpg?raw=true "gb.device.ultrasonic")
2. Connect Wires to Raspiberry Pi
![Photo](Ultrasonic Wiring 2.jpg?raw=true "gb.device.ultrasonic")

###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.ultrasonic.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.ultrasonic.Test/.src/FMain.class  

![Photo](Demo Code Long Range.png?raw=true "gb.device.ultrasonic")
![Photo](Demo Code Short Range.png?raw=true "gb.device.ultrasonic")

(The pins are On and Off so fast you will not see them on the GPIO Live Monitor)

Thanks  
Matt

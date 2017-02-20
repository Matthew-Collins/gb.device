#gb.device.piconzero
Control 6 Servos, 1 Ultrasonic Distance Sensor, 4 Obstable Sensors, 2 Motors and more.

![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - All.jpg?raw=true "gb.device.piconzero")

##Getting Started on Raspberry Pi:
1. Install gb.device.gpio, gb.device.i2c, gb.device.ultrasonic, gb.device.piconzero from:  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-gpio_0.0.3-1_all.deb  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-i2c_0.0.1-1_all.deb  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-ultrasonic_0.0.1-1_all.deb  
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-piconzero_0.0.1-1_all.deb  

2. Open Gambas
3. Start a new project or open an existing one
4. Goto Menu: Project > Properties > Components > Check/Tick:  
    gb.device.piconzero  
	gb.device.i2c  
	gb.device.gpio  
	gb.device.ultrasonic  
![Photo](Test Code Select Component.png?raw=true "gb.device.piconzero")

##Turn Off Raspberry Pi and Do Wiring:

### Servos
1. Connect the Servo Directly to the Picon Zero Output Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Servos.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Servos Wiring.jpg?raw=true "gb.device.piconzero")
  
### Ultrasonic Distance Sensor
1. Connect the Ultrasonic Directly to the Picon Zero Ultrasonic Connector
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Ultrasonic - Wiring.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Ultrasonic.jpg?raw=true "gb.device.piconzero")
  
### Obstable Avoidance Sensor
1. Connect the Obstable Directly to the Picon Zero Input Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Obstacle Sensors Wiring.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Obstacle Sensors.jpg?raw=true "gb.device.piconzero")
  
### Motors
1. Wire the Motors to the Motor H-Bride Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Motors - Wiring 1.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Motors - Wiring 2.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Motors.jpg?raw=true "gb.device.piconzero")
  
## Reboot and Start Testing Code, Tab by Tab:
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Servos.png?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Ultrasonic.png?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Obstacle Sensors.png?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/imagesPicon Zero - Motors.png?raw=true "gb.device.piconzero")
  
###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.piconzero.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero.Test/.src/FMain.class  

Thanks  
Matt

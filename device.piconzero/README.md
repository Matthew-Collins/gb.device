#gb.device.piconzero
Control 6 Servos, 1 Ultrasonic Distance Sensor, 4 Obstacle Sensors, 2 Motors and more.

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
    gb.device.gpio  
    gb.device.i2c  
    gb.device.ultrasonic  
    gb.device.piconzero  
![Photo](Test Code Select Component.png?raw=true "gb.device.piconzero")

##Turn Off Raspberry Pi and Do Wiring:

### Servos
1. Connect the Servos Directly to the Picon Zero Output Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Servos.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Servos Wiring.jpg?raw=true "gb.device.piconzero")
  
### Ultrasonic Distance Sensor
1. Connect the Ultrasonic Directly to the Picon Zero Ultrasonic Connector
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Ultrasonic.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Ultrasonic - Wiring.jpg?raw=true "gb.device.piconzero")
  
### Obstacle Avoidance Sensor
1. Connect the Obstacle Sensors Directly to the Picon Zero Input Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Obstacle Sensors.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Obstacle Sensors Wiring.jpg?raw=true "gb.device.piconzero")
  
### Motors
1. Wire the Motors to the Motor H-Bride Section
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Motors.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Motors - Wiring 2.jpg?raw=true "gb.device.piconzero")
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Motors - Wiring 1.jpg?raw=true "gb.device.piconzero")
  
## Reboot and Start Testing Code, Tab by Tab:
### Servos
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Servos.png?raw=true "gb.device.piconzero")
  
### Ultrasonic Distance Sensor
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Ultrasonic.png?raw=true "gb.device.piconzero")
  
### Obstacle Avoidance Sensor
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Obstacle Sensors.png?raw=true "gb.device.piconzero")
  
### Motors
![Photo](https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero/images/Picon Zero - Motors.png?raw=true "gb.device.piconzero")
  
###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.piconzero.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.piconzero.Test/.src/FMain.class  

Thanks  
Matt

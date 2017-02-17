#gb.device.gpio

Open, Read, Write and Close GPIO pins via Sysfs.
![Photo](Raspberry Pi - GPIO Pin Layout Diagram.jpg?raw=true "gb.device.gpio")

##Prerequisites:
https://www.kernel.org/doc/Documentation/gpio/sysfs.txt  
(You may find this is already installed).

##Getting Started on Raspberry Pi:
1. Install gb.device.gpio from: 
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-gpio_0.0.3-1_all.deb
2. Open Gambas
3. Start a new project or open an existing one
4. Goto Menu: Project > Properties > Components > Check/Tick: gb.device.gpio
5. Write some code...
6. Dim Pin as New GPIO_Pin(Any Pin BCM Number i.e 17 which is physical pin 11)
7. Print Pin.GetValue
![Photo](Test Code Select Component.png?raw=true "gb.device.gpio")

###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.gpio.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.gpio.Test/.src/FMain.class

![Photo](Test Code Demo with GPIO Monitor.png?raw=true "gb.device.gpio")

###Also download and try out this live and colourful Pin monitor by Charlie Ogier:  
https://github.com/charlie-ogier/gpio

Thanks  
Matt

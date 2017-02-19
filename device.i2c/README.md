#gb.device.i2c

Open, Read, Write to i2c / SMBus Devices via i2c-tools.
![Photo](i2cDetect and i2cDump.png?raw=true "gb.device.i2c")

#Prerequisites:
sudo apt-get install i2c-tools

##Getting Started on Raspberry Pi:
1. Install gb.device.i2c from: 
https://github.com/Matthew-Collins/gb.device/blob/master/Install/0.0.1/debian/gambas3-gb-device-i2c_0.0.1-1_all.deb
2. Open Gambas
3. Start a new project or open an existing one
4. Goto Menu: Project > Properties > Components > Check/Tick: gb.device.i2c
5. Write some code...
6. Dim SMBus as New i2c(1, &H22)
7. Print SMBus.Read8(&HA6)
![Photo](Test Code Select Component.png?raw=true "gb.device.i2c")

###More Code Examples see:
https://github.com/Matthew-Collins/gb.device/tree/master/device.i2c.Test  
https://github.com/Matthew-Collins/gb.device/blob/master/device.i2c.Test/.src/FMain.class

![Photo](Test Code Demo with i2c Tools.png?raw=true "gb.device.i2c")
  
(Note: how the values are reversed, this is called Big-Indian and Little-Indian, one to watch out for)

Thanks  
Matt


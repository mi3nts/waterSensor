# Instructions: Connecting AIRMAR Weatherstation 220WX via USB to Linux OS

## Necessary Materials

-	AIRMAR WeatherStation 220WX sensor
-	10 pin WeatherStation connector (7-pin output, 10-pin input)
-	10 pin WeatherStation to serial port converter
-	12VDC power supply
-	RS-485 to RS-232 converter 
-	RS-232 to USB converter
-	Computer with Linux OS

## Connect Sensor to Computer

-	Connect RS-232 end of RS-485 to RS-232 converter to RS-232 to USB converter
-	Connect RS-485 end of RS-485 to RS-232 converter to serial port end of 10 pin WeatherStation to serial port converter
-	Connect 10 pin WeatherStation connector to 10 pin WeatherStation to serial port converter
-	Connect AIRMAR WeatherStation 220WX sensor to 10 pin WeatherStation connector
-	Plug USB end of RS-232 to USB converter into computer
-	Plug 12VDC power supply to 10 pin WeatherStation to serial port converter

## Screen USB Port at 4800 Baud Rate

-	Open new Terminal on Linux OS
-	Type the following commands in Terminal

```ls –l /dev/ttyUSB*``` </br>
```screen /dev/ttyUSBx 4800``` </br>





<pre>
This repository is for backing up and sharing my PCB designs done in KICAD

ESP8266_Water_Sensor
	- This PCB uses an ESP8266 to make an IOT device with 3 functions:
		1) Reads the resistance from a water level sensor to determine how full a water tank is
		2) Has a header to connect an MPU6050 accelerometer
		3) Can control WS2811 light strips
	- The PCB is powered by 12V and uses a buck converter to step it down to 3.3V for the ESP8266 and the MPU6050
	- The ESP8266 communicates to Home Assistant running on a Raspberry Pi over WIFI
	- Designed to fit in the 1551TFLGY plastic enclosure

ESP32_12v_Relay
	- This PCB uses an ESP32 to make an IOT device
	- The board uses MOSFETs to switch on and off 12V power to up to 4 devices
	- Designed to control lights and solenoids, but can be used for other functions as well
	- MOSFETS can be controlled by hardware PWM outputs from the ESP32
	- The PCB is powered by 12V and uses a buck converter to step it down to 3.3V for the ESP32
	- The ESP32 communicates to Home Assistant running on a Raspberry Pi over WIFI
	- Designed to fit in the 1551TFLGY plastic enclosure
</pre>

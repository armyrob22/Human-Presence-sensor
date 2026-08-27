# Human-Presence-sensor
![assembled board v2](documents/PCBv2.png)
This is my second version of this board. My first board had many errors and was basically unusable. This design puts the ESP32 on the PCB and lets just the mmWave 24Ghz radar board plug into a pin header. This design forced me to learn how to really design a buck converter circuit so i can take the 5V USB input power and drop it down to 3.3V required for the MCU. I took it a step further and I really drilled down on learning the physic's and the equations to derive what you need for a buck converter.

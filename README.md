# testlap

## reqs

pi zero w  
usb to go connector  
usb hub (powered)  
u-blox usb gps device (test on vk172)  
usb audio input (and output? I use a usb->3.5mm TRRS connector)  
(optional) pi camera module  
(optional) nyrius orion  
usb battery with 2 outputs, one at least 2 amp.  
  
gpsd 3.20+ & gpsd-clients  
pulseaudio  
[talkkonnect](https://github.com/talkkonnect/talkkonnect)  
picamera  

### u-blox 7 update rate 

Set to 10hz:
```ubxtool -p RATE,100 -P 14.00```



# object-detection-node
The aim is to create an IOT device capable of distinguishing between animal species. It is based on a raspberrypi zero 2 w, and a lorawan transmitter to be able to send data over long distances.  

LINKS TO HELPFUL STUFF:

I had problems with opencv "cv2" module, this tutorial shows how to compile opencv on the RaspberryPi in order to get things working
https://qengineering.eu/install-opencv-lite-on-raspberry-pi.html

A basic model to test the object detection, I modified the TFLite_detection_webcam.py to work without monitor, and instead print the results to command line
https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/blob/master/Raspberry_Pi_Guide.md

As of winter 22, probably the only working example of the lora e5 min. Hopefully there will be more because the c/c++ underneath is horrible
https://github.com/eivholt/snowmonitor/tree/main/LoRa-E5-Mini-EndNode

More links for the lora e5 mini
https://wiki.seeedstudio.com/LoRa_E5_mini/
https://ashutosh952.medium.com/lora-e5-dev-board-example-code-in-stm32-cube-ide-led-blink-cd837d0fa19e




E5 MINI DEBUGGING CONNECTIONS

e5 pin -----  stlink pin
5v     -----  pin1
SDWIO  -----  pin7
SWDLK  -----  pin9
GND    -----  pin8
SCK    -----  pin19


![IMG_20220104_171939](https://user-images.githubusercontent.com/84034458/166166712-8ec16e81-aac2-4984-82ad-1755e1fc22df.jpg)

![3001615286723_ pic_hd](https://user-images.githubusercontent.com/84034458/166166773-a717120d-cd26-414a-a979-4575ddb80c17.jpg)

![ARM_JTAG_SWD_Header](https://user-images.githubusercontent.com/84034458/166166742-a7f3f86a-922c-458e-ada1-14f9c5f1b489.png)

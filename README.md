# SerialEEPROM
Changing value of constant variable by reading the EEPROM. And storing EEPROM data from Serial Monitor


# Why this?
You can change the constant values which are store in EEPROM. 

Lets say you have a blinking sketch uploaded in the arduino with 1 sec delay. But you want to change the delay time tio 5 seconds(Lets' a scenerio where you cannot plug the arduino for programming)... If you use this,you can attach a bluetooth HC0-5 module to the arduino,You can change the timing using bluetooth serial app for Smartphone or by using another HC05 which attache to USB to serial convertor

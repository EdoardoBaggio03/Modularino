![Immagine 2023-02-16 152313](https://user-images.githubusercontent.com/102879259/219391611-ac6b1fe4-5904-4116-b0f2-95f73ac257cf.png)
![bottom](https://user-images.githubusercontent.com/102879259/219391675-64891d52-dc83-44f4-a928-20fb22e97843.png)
# Modularino
Modularino is a whole system composed of multiple PCBs: there's the motherboard wich has the necessary components to connect all the modules and the connectors to plug in the modules. The modules consists of multiple MPU types with diffrent carateristics:



- Atmega168p-au: The classical "arduino" chip, with lots of different I/O ports, digital and analog ones. It has plenty of memory to store your programs and data without needing an external memeory chip.


- ESP-12E: Similar memory carateristics to the Atmega168p-au chip, with less analog pins but with built-in Wi-Fi feature so you can connect your whole project system with the internet and make Iot devices

Modularino motherboard works as a development board so you have all the GPIO connectors and others to make your best electronics projects!

By using the mezzanine connectors for connecting the modules to the motherboard you can save up a lot of space and money since it's one of the cheapest type of connectors with great mechanical characteristics



To summarize: Modularino is a base board with all the breakout GPIO pins where you can attach all the sensors, actuators ecc for your project like an arduino or a raspberry board, the diffrence is that it hasn't a microcontroller installed but you can choose the microcontroller module and snap it on top of the motherboard based on your necessity, modularino has an usb type-c port already installed.



For further information and schematics check the modularino github page: https://github.com/EdoardoBaggio03/interchangeable-usb-connectors


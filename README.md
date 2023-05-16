This GITHUB repo contains all the codes and directories and the headers for the smart dustbin embedded systems project.
The main code is available inside core-> src



The proposal

Our proposed project is a smart dustbin management system that aims to improve waste management and promote a cleaner environment. The system will use ultrasonic sensors placed in the dustbin to detect the level of waste. The data is then sent to a module that alerts those in charge that it's time for disposal through an SMS message and in addition, A LED light will be used to reflect that the dustbin has reached its peak level and the trash needs to be emptied. The project can be further improved later on for bigger waste containers using more or better sensors.

How the system works:

The system is designed to operate with any dustbin equipped with a mechanical opener and utilizes a sensor to determine the distance between the sensor and the depth of the bin, enabling the system to determine the bin's empty depth. If the distance is 0.2% or less for two consecutive readings, the system will change the flag to 1 and send an alert to the user notifying them that the bin is full and requires emptying. When the distance is greater that 0.2 if the bin’s height it turns the flag to 0, so the LED turns off.

Next Milestone

Send a message to the user once the trash is emptied.
Connect the sensor to a power source.
Connect an external LED.
Connect the GSM model.

link for the code and demo on drive

https://drive.google.com/drive/u/1/folders/1UjGRkwK7j5Lc7K5G9Njl28aMKsLREUUy
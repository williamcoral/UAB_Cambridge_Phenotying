# UAB_Cambridge_Phenotying
Weight Measuring Component
Hello Marius
This is the repository where you can find the requested circuit. Because some of the device features were not specified in your message, such as:
1. Sampling rate
2. Communication protocol for communication between sensors and microcontroller.
3. How to program the microcontroller and display the data.
4. Type of power supply to be used
5. Where the data will be displayed
6. Operating voltage
7. EMI-EMC

Thanks to this lack of information, I took certain liberties in the design of the circuit, such as:
1. Sampling rate will be 1k samples per second
2. The communication protocol will be I2C between the sensor and the microcontroller.
3. The microcontroller will be programmed through the usb port (micro USB connection). Data can be displayed using an OLED I2C panel or a computer, via the micro USB port.
4. This device will be able to work with at least two cell Lipo batteries (up to 3 cells 3S). as well as an external power supply or via a micro USB cable.
5. The data can be displayed using an OLED panel compatible with I2C communication or a computer through the USB port.
6. The input voltage range is from 4.5 to 21V.
7. mask on top and bottom layer.

I apologize in advance for taking so long to send the circuit, but from Thursday of last week to Tuesday of this week I was traveling. It was fun doing this circuit and I hope you like it.

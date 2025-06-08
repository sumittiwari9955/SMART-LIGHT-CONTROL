# COMPANY:- CODTECH IT SOLUTION
# NMAE:- SUMIT KUMAR
# INTERN ID:- CT04DF1595
# DOMAIN:- Internet Of Things
# DURATION:- 4 WEEKS
# MENTOR:- NEELA SANTOSH
# DESCRIPTION #
# OUTPUT:-
![Image](https://github.com/user-attachments/assets/4fff4b05-0417-4287-9a39-c96c127210d1)
Smart LED Light Using Arduino and HC-05 Bluetooth Module
The concept of smart lighting has become a fundamental part of modern home automation. A simple yet effective way to create a smart lighting system is by using an Arduino microcontroller in combination with an HC-05 Bluetooth module and a basic LED light. This project enables users to wirelessly control an LED light from their smartphone using Bluetooth technology.

Components Used
The main hardware components used in this system are:

Arduino Uno or Nano – the central microcontroller that processes instructions.

HC-05 Bluetooth Module – a wireless module that allows communication between the Arduino and a smartphone via Bluetooth.

LED Light – the output device controlled by the Arduino.

Resistor – used to protect the LED from excess current.

Breadboard and Jumper Wires – for making temporary connections without soldering.

Android Smartphone with a Bluetooth Terminal App – used to send control commands to the system.

How It Works
The system functions on the principle of wireless serial communication. The HC-05 Bluetooth module is connected to the Arduino and paired with a smartphone. When a user sends a command from the mobile device using a Bluetooth terminal app, the HC-05 receives the command and passes it to the Arduino.

The Arduino interprets these commands and controls the LED accordingly. For example, sending a specific character can turn the LED ON, while sending a different character can turn it OFF. This simple communication process enables users to control the LED without any physical switches, using just their smartphone.

Circuit Design
The circuit design is simple. The HC-05 module is powered through the Arduino’s 5V and GND pins. Its TX (transmit) and RX (receive) pins are connected to the Arduino’s RX and TX pins for communication. The LED is connected to one of the digital pins on the Arduino, along with a resistor to prevent overcurrent. The breadboard is used to organize and secure the components, and jumper wires are used to connect everything.

Applications and Advantages
This smart LED light system serves as an excellent introduction to both Bluetooth communication and microcontroller-based automation. It demonstrates how electronic devices can be controlled remotely without complex hardware.

Key benefits include:

Low cost: Uses inexpensive components, making it accessible to beginners.

Portability: Can be easily modified or expanded into more complex systems.

Hands-free control: Offers basic home automation functionality.

Educational value: Ideal for learning about Arduino, Bluetooth technology, and serial communication.

Possible Enhancements
This project can be expanded in several ways. Instead of a single LED, multiple LEDs or high-power bulbs can be controlled using relays. You can also add sensors like LDRs (Light Dependent Resistors) for automatic lighting based on ambient light. For advanced functionality, you could integrate voice control, timer settings, or even upgrade to Wi-Fi modules (like ESP8266 or ESP32) for internet-based control.

In conclusion, building a smart LED light using an Arduino and HC-05 Bluetooth module is a practical and educational project that introduces the basics of home automation, offering hands-on experience with embedded systems and wireless communication.









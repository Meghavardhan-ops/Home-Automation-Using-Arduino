# Home-Automation-Using-Arduino
It’s an IoT-based project that connects home appliances with Arduino ⚙️.

ABOUT THE PROJECT
In today's era, technology can enhance human life 🌟. Technology is evolving decade by decade 🔄. Automation was once science fiction, but not today 🚀. By combining the latest technology with home, we can build an awesome home 🏡. With the Arduino Uno and Windows 10 or 11, we can build a home automation system capable of operating home devices automatically 🖥️🔌.

Getting Started
Before starting the project, let's understand the basics first 📚. Consider the following image (overall configuration) 🖼️:
![pc1](https://github.com/user-attachments/assets/bee7c505-1a2a-4190-93c7-b326e372866d)

Configuration for Room
Now considering the room scenario 🏠, an Arduino UNO will control devices and read sensor data ⚙️📊. The figure "Room Architecture" depicts how the Arduino UNO connects with the devices and sensors 🔗.

The room has multiple controllable devices (i.e., Light(s) 💡, Fan 🌀, Wall Socket(s) 🔌, etc.), one Passive IR (to detect human presence in the room) 👤, one temperature sensor (LM35) (to collect room temperature) 🌡️, and LDR (to detect light intensity near the room window) ☀️.

![pc2](https://github.com/user-attachments/assets/35f43549-705d-428d-9f2c-801a2459c279)

Configuration of Different Sensors
Servo Motors ⚙️ Servo motors are geared DC motors with closed-loop circuitry incorporated within them 🔄. The basic configuration of a servo motor consists of a DC motor, gearbox, potentiometer, and control circuit 🔧.

The DC motor is used to move a gearbox with a large reduction ratio. The final shaft imposes a force on the external load and simultaneously acts on the axis of the feedback potentiometer 🛠️. The potentiometer senses the position of the axis and sends a corresponding voltage to an operational amplifier 📉. This voltage is compared to the input voltage, which determines the desired position of the shaft, producing a voltage in the output of the comparator 🔋. This voltage powers the motor such that the shaft moves in the necessary direction to align with the angle that corresponds to the voltage applied to the input 🎯.

![pc3](https://github.com/user-attachments/assets/959d4cfe-cfff-42d8-baf9-9a83d36a7265)

LM35 🌡️
The LM35 is a precision IC temperature sensor with its output proportional to the temperature (in °C) 📏. The sensor circuitry is sealed, which means it is not subjected to oxidation and other processes 🌿🔒.

![pc4](https://github.com/user-attachments/assets/7667bd9e-98b2-4001-896a-557ef7f8c929)

PIR Sensor 👤
The pin configuration of the PIR sensor is shown in the figure 📐. The PIR sensor consists of three pins: ground, signal, and power at the side or bottom. Generally, the PIR sensor power is up to 5V, but the large size PIR modules operate a relay instead of direct output 🔌

![pc5](https://github.com/user-attachments/assets/68351926-b37f-4e33-b41b-8e46c6bd8bf0)

HC-05 (Bluetooth) 📶
To make a link between your Arduino and Bluetooth, do the following:

Go to the Bluetooth icon 🔷, right click and select Add a Device ➕

Search for a new device 🔎. Our Bluetooth module will appear as HC-05 📱, and add it ✅

The pairing code will be 1234 🔒

After making a pairing, we can now program the Arduino and upload a sketch to send or receive data from the computer 🖥️➡️📊

![ard](https://github.com/user-attachments/assets/1f383e03-f242-4e30-91e9-0e7bbc547090)

.

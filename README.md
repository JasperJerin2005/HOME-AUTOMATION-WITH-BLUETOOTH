# HOME-AUTOMATION-WITH-BLUETOOTH
COMPANY: CODTECH IT SOLUTIONS

NAME: JASPER JERIN J

INTERN ID:
CT04DH872
DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

#OUTPUT 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/35233781-e0f6-47f2-834a-4e06f993ab5e" />
DESCRIPTION:
This internship task involves creating a home automation system using an Arduino Uno board, LEDs (representing appliances), and serial communication that simulates Bluetooth input. The goal is to control household devices such as a light, a bulb, and a fan using single-character commands sent from a serial monitor or Bluetooth terminal. Each device's ON/OFF state is toggled based on the received command and is indicated using LEDs.

The hardware setup includes three LEDs connected to Arduino digital pins 2, 3, and 5 through current-limiting resistors. The Arduino receives commands via the Serial interface (e.g., 'A' for turning the light ON, 'a' to turn it OFF), interprets the input, and performs the corresponding digital output action. The Serial Monitor also provides feedback confirming the operation of each device.

CODE DESCRIPTION:
The code initializes the serial communication at 9600 baud rate and sets up the three output pins for controlling the appliances. A character variable is used to store incoming serial data. Inside the loop(), the Arduino checks if a command has been received using Serial.available() and processes it through a switch statement.

Each case in the switch corresponds to turning a specific device ON or OFF, and a feedback message is sent via Serial.println() to inform the user. This simple logic mimics Bluetooth-based control and provides clear interaction through serial output. Though the simulation uses the Serial Monitor, it can be adapted to work with Bluetooth modules like HC-05 for real wireless communication.

APPLICATION:
This project demonstrates a foundational concept in IoT and home automation. It showcases how everyday devices can be digitally controlled through microcontroller programming. The system is ideal for use in smart homes where lights, fans, or other appliances can be automated or remotely controlled.

Real-world applications include:

Smartphone-based home appliance control via Bluetooth,

Energy-efficient smart lighting systems,

Automation in elderly care homes for ease of access,

Educational setups to demonstrate basic IoT concepts,

Prototypes for scalable smart home platforms.

The project highlights core embedded systems concepts such as digital output control, serial communication, command interpretation, and user feedback mechanisms—making it perfect for beginners in electronics and automation.


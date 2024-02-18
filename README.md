# Interacive Data Processor ⚡️

**Explanation:**
This was a design team project put together to master CAN and serial interfaces by utilizing the Teensy 4.1 with KiCad. Please refer to the "Circuit-Explanation.pdf" for technical details. 

## Skills needed:
- Understanding of how CAN Bus networks are used/function
- Understanding of how serial communications are used/function
- Understanding of how µControllers can communicate over CAN Bus
and Serial

## Component Overview:
- Teensy 4.1: Manages the communication over CAN bus and serial interfaces, featuring an ARM Cortex-M7 processor.
- Motor Controllers (SPARK MAX, Victor SP): These controllers manage brushless and brushed DC motors, with SPARK MAX utilizing CAN bus for communication, while Victor SP relies on PWM.
- Sensors: Including MPU-6050 for motion tracking, BMP280 for atmospheric pressure and temperature, and HC-SR04 for ultrasonic distance measuring, enhancing the project's capability to interact with the environment.
- Communication Protocols: Utilizing I2C for sensor data aggregation and SPI for LCD module communication, ensuring efficient data exchange.
- LED Control: WS2812B LEDs are used for visual feedback, controlled via PWM.
- Logic Level Conversion: BOB-12009 modules are employed to interface between 3.3V and 5V logic levels, ensuring compatibility across components.
- Additional Microcontroller: An Arduino Nano serves as a supplementary processing unit, communicating serially with the Teensy for expanded functionality.



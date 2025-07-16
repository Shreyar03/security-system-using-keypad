# Security-system-using-keypad

This is a simple security system built using the **AT89C51 microcontroller**, where a user must enter a 4-digit password through a keypad. If the password is correct, access is granted (motor turns ON); otherwise, access is denied. After 3 wrong attempts, the system gets blocked temporarily.

# Abstract

To design and implement a keypad based pin protective security system, the system consists of a keypad, LCD, relay, motor as main components, if the user enters the wrong input the system does not open trigger the motor instead of it shows LCD as Access denied Try Again if the user enters wrong in more than 3 times, it shows LCD as Temporarily blocked and it makes alert by triggering buzzer, otherwise, if the user enters right pin it shows LCD as Access granted and triggers a motor.

# What This Project Does

- Accepts 4-digit password input via 4x3 keypad
- Displays `*` on LCD for each entered digit
- Compares input with the preset password (`1234`)
- Shows **"Access Granted"** or **"Access Denied"** on the LCD
- Controls a motor through relay on successful access
- Locks system after 3 wrong attempts

# Components Used

1)A700D107M006ATE018
  Name: Aluminum Electrolytic Capacitor
  Explanation: Stores electric charge
2)AT89C51
  Name: Microcontroller (8051 family)
  Explanation: Controls digital operations
3)BUTTON
  Name: Push Button Switch
  Explanation: User input device
4)C3225Y5V1A476Z
  Name: Multilayer Ceramic Capacitor
  Explanation: Stabilizes power supply
5)CRYSTAL
  Name: Quartz Crystal Oscillator
  Explanation: Generates clock signal
6)KEYPAD-PHONE
  Name: Matrix Keypad
  Explanation: Inputs multiple keys
7)LED-GREEN
  Name: Green Light Emitting Diode
  Explanation: Indicates device status
8)LED-RED
  Name: Red Light Emitting Diode
  Explanation: Alerts or signals
9)LM016L
  Name: 16x2 LCD Module
  Explanation: Displays text output
10)MOTOR
  Name: DC Motor
  Explanation: Converts electricity motion
11)PULLDOWN
  Name: Pulldown Resistor
  Explanation: Ensures logic low
12)RELAY
  Name: Electromechanical Relay
  Explanation: Switches high voltage
13)ULN2003A
  Name: Darlington Transistor Array
  Explanation: Drives inductive loads
 
# Tools Required

**Proteus 8** – For circuit simulation  
**Keil µVision** – For writing and compiling C code  
**8051 Programmer** (optional, for hardware implementation)


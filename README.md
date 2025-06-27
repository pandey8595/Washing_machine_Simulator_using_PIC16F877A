# Washing_machine_Simulator_using_PIC16F877A
The Washing Machine Simulator is a microcontroller-based embedded system project designed to mimic the operations of a basic automatic washing machine. Using the PIC16F877A microcontroller, the system controls various stages of a washing cycle including washing, rinsing, and spinning by interfacing multiple hardware peripherals.

🔧 Key Components Used:
PIC16F877A Microcontroller: The core controller that manages all operations.

16x2 Character LCD: Displays current washing status, time remaining, and cycle stages.

Push Buttons (Tactile switches): Used as input for selecting wash modes or starting the machine.

Timer2 Module: Provides time-based control for different wash stages.

Interrupts: Used for real-time control and responsiveness to user input.

Relays (optional): Can simulate control of motor and water valves.

🔄 Functional Overview:
Startup: The LCD displays a welcome message and waits for user input.

Mode Selection: User selects washing mode using push buttons (e.g., Quick Wash, Normal, Heavy).

Operation Cycle:

Washing: Agitates the load using simulated motor control.

Rinsing: Simulates water flow control.

Spinning: Simulates high-speed motor operation for drying.

Display Updates: Each stage and time countdown is shown on the LCD.

Completion: The system signals the end of the cycle and resets.

🎯 Learning Outcomes:
Hands-on experience with PIC programming in Embedded C.

Practical understanding of peripheral interfacing (LCD, switches, timer, etc.).

Use of interrupts and timers for time-critical applications.

Exposure to real-world embedded system design for automation.


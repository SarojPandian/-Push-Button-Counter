# Push Button Counter Using Microcontroller with Debouncing and Display Output

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAROJ KANNA J

*INTERN ID*: CT04DN1027

*DOMAIN*: EMBEDDED SYSTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# Description

+ The aim of this project is to design an embedded system that uses a microcontroller to precisely count and display the number of times a push button was pressed.  The mechanical "bouncing" of the button, which can produce many counts for one push, is the main problem using such devices. Software-based debouncing techniques are used to get around problem and guarantee precise and accurate counting.

+ The system uses a digital input pin to detect the button press. A debounce routine is incorporated using delay to filter out spurious signals caused by bouncing. Each valid press increments a counter, which is then displayed on an output interface, 16x2 LCD screen.

+ This project demonstrates key embedded system principles like output display, software debouncing, digital input processing, and real-time counting.

## Software Used

1. **Proteus 8 Professional**
   - A professional-level circuit simulation software used to simulate microcontroller-based projects. It allows real-time visualization of the embedded system's functionality without needing physical hardware. It supports direct import of .hex files generated from Arduino IDE for simulation.

2. **Arduino IDE**
   - An open-source software used for writing, compiling, and uploading code to Arduino boards. It supports embedded C/C++ programming with many built-in libraries, simplifying the process of working with peripherals like buttons and LCDs.
  
3. **Hex File Generator**
   - The Arduino IDE was used to compile the sketch into a .hex file, which was then loaded into the Proteus Arduino model for simulation.
  
## Components Used

1. **Microcontroller: Arduino Uno R3**
   - A widely-used open-source microcontroller board based on the ATmega328P. It offers digital and analog I/O pins, easy USB connectivity, and is ideal for beginner-level embedded projects.
  
2. **Input Device: Push Button Switch**
   - Used as the primary user input for triggering count increments.

3. **Output Device: 16x2 LCD Display (Alphanumeric)**
   - Used to display the count of button presses in real-time. Operated in 4-bit mode to conserve Arduino I/O pins.

## Circuit Diagram

![Image](https://github.com/user-attachments/assets/b5e90c6a-0148-4dee-bc53-180c51e3c5bb)

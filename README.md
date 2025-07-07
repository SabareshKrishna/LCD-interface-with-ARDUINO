# LCD Interfacing with Arduino Uno (Tinkercad Simulation)

This project demonstrates how to interface a 16x2 LCD with an Arduino Uno and use a potentiometer to control display contrast. The LCD shows real-time information, fully simulated and tested using Tinkercad.

## 🛠️ Components Used
- Arduino Uno  
- 16x2 LCD (non-I2C)  
- 10kΩ Potentiometer  
- Breadboard  
- Jumper wires  
- Tinkercad Circuit Simulator

## 🔌 Circuit Connections

| LCD Pin | Function         | Arduino Pin / Connection       |
|---------|------------------|--------------------------------|
| 1 (VSS) | GND              | GND                            |
| 2 (VDD) | Power            | 5V                             |
| 3 (VO)  | Contrast Control | Potentiometer (center pin)     |
| 4 (RS)  | Register Select  | Pin 12                         |
| 5 (RW)  | Read/Write       | GND                            |
| 6 (E)   | Enable           | Pin 11                         |
| 11-14   | Data (D4–D7)     | Pins 5, 4, 3, 2                |
| 15-16   | Backlight        | 5V (via resistor), GND         |




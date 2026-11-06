<img width="828" height="1152" alt="image" src="https://github.com/user-attachments/assets/da25c4e0-c99e-448c-990a-3039512d4ced" /># BJT Transistor Switching & Bias Control Circuit

A solid-state switching circuit using an NPN bipolar junction transistor (BJT)
to control an LED from a 9 V DC supply. Built on a breadboard in the Electronics
lab at Astana IT University and recreated as a simulation in Autodesk Tinkercad.

## How it works
- A potentiometer and a 1 kΩ base resistor form a variable voltage divider
  that controls the transistor's base current
- Turning the potentiometer moves the transistor between two regimes:
  - **Cut-off** – base current is too low, the transistor is off, the LED is off
  - **Saturation** – the transistor fully conducts, the LED is on
- A 470 Ω resistor limits the LED current and protects the LED at any
  potentiometer position

## What I did
- Assembled and tested the circuit on a breadboard in the lab
- Recreated it in Tinkercad and identified that without a current-limiting
  resistor the LED is overloaded in saturation; added a 470 Ω resistor to fix it
- Analysed transistor biasing, switching threshold and load protection

## Components
NPN BJT · LED · 9 V battery · potentiometer · 1 kΩ and 470 Ω resistors · breadboard

## Demo
**Real circuit (Electronics lab):**
<img width="828" height="1152" alt="image" src="https://github.com/user-attachments/assets/99d654a1-7d48-4520-a873-0b5e7b3a5972" />


**Video:**


https://github.com/user-attachments/assets/eada2afa-b4bf-438b-86ed-cd569bc0ac8a



**Tinkercad simulation:**
<img width="1280" height="811" alt="image" src="https://github.com/user-attachments/assets/74393810-ef05-4086-b4a3-0aabd2d068d3" />


Interactive simulation: (https://www.tinkercad.com/things/gUp1OqHdXN9-bjt-transistor-switch)

## Skills
Circuit assembly · Transistor biasing · Voltage dividers · Current limiting ·
Circuit simulation (Tinkercad)

## Author
Duisengaliyeva Adel, Astana IT University (ST-2502)

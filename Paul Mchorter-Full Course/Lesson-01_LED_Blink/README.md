
# 🔧 Lesson 01 - LED Blink (Arduino Basics)

## 📌 Course
Paul McWhorter - Arduino Full Tutorial Series

---

## 🎯 Objective
The goal of this lesson is to understand how to:
- Configure Arduino digital pins
- Control digital output (HIGH / LOW)
- Use delay() for timing
- Create a basic LED blinking circuit

---

## 🧠 Concepts Learned
- digitalWrite()
- pinMode()
- delay()
- Arduino program structure (setup & loop)

---

## ⚙️ Components Used
- Arduino Uno
- LED
- 330Ω Resistor
- Breadboard
- Jumper wires

---

## 🔌 Circuit Description
The LED is connected to digital pin 13 of the Arduino through a resistor to limit current. The cathode (short leg) is connected to GND.

---

## 🧪 Simulation (Wokwi)

👉 Live Simulation Link:  
https://wokwi.com/projects/461188922729620481

---

## 💻 Code

```cpp
void setup() {
  pinMode(12, OUTPUT);
}

void loop() {
  digitalWrite(12, HIGH);
  delay(1000);
  digitalWrite(12, LOW);
  delay(1000);
}

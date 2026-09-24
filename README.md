# 🚦 Arduino Traffic Light System

## 📌 Project Description

This project is a simple traffic light simulation developed using an Arduino Uno and three LEDs.

The system controls red, yellow, and green LEDs in a sequence similar to a real-world traffic signal. Each LED remains ON for a specific duration before switching to the next signal.

## 🛠️ Components Used

- Arduino Uno
- Red LED
- Yellow LED
- Green LED
- 220Ω Resistors
- Jumper Wires

## ⚙️ Working

The Arduino controls three LEDs using digital output pins:

- 🔴 Red LED → Stop
- 🟡 Yellow LED → Wait
- 🟢 Green LED → Go

The sequence continuously repeats:

**Red → Yellow → Green → Red**

## 🔌 Pin Connections

| Component | Arduino Pin |
|---|---|
| Red LED | D8 |
| Yellow LED | D9 |
| Green LED | D10 |

Each LED is connected through a 220Ω resistor.

## 💻 Programming

The project is programmed using Arduino C/C++.

## 🧪 Simulation

The circuit can be simulated using Tinkercad Circuits.

## 🎯 Objective

The objective of this project is to understand Arduino digital output control, LED interfacing, timing functions, and basic embedded-system programming.

## 🚀 Future Improvements

- Add pedestrian crossing control
- Add a push button
- Add a countdown display
- Add an ultrasonic sensor for smart traffic detection
- Expand the system for multiple traffic signals

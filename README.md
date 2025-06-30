# Automatic Light Control Using LDR

This project is a simple and practical automatic lighting system that turns a lamp or light on/off based on ambient light levels using an LDR (Light Dependent Resistor). It includes both analog and microcontroller (Arduino) implementations, with full Proteus simulation and PCB layout using EasyEDA.

---

## 🔧 Features

- Automatic control of a light based on surrounding brightness
- Two versions:
  - Analog circuit using transistor and relay
  - Arduino-based version using analogRead + digitalWrite
- Proteus simulation for both versions
- PCB design using EasyEDA
- Cost-effective and beginner-friendly

---

## 📐 Schematics & Design Tools

| Component         | Tool Used     |
|-------------------|---------------|
| Analog Circuit    | Proteus 8     |
| Arduino Simulation| Proteus 8     |
| PCB Design        | EasyEDA       |
| Programming       | Arduino IDE   |

---

## 🧰 Bill of Materials

| Component        | Quantity |
|------------------|----------|
| LDR              | 1        |
| 10k Resistor     | 1        |
| NPN Transistor (e.g. BC547) | 1 |
| Relay Module     | 1        |
| Arduino Uno      | 1 *(for digital version)* |
| LED / Bulb       | 1        |
| Power Supply     | 5V / 9V  |

---

## ⚙️ How It Works

- **Analog Version**:  
  Uses a voltage divider with LDR. When light is low, voltage across base of the transistor increases, activating the relay to turn on the light.

- **Arduino Version**:  
  LDR is connected to an analog input. Arduino reads light level and controls output pin connected to a relay or LED.
  

## 💾 Files Included

- `analog_circuit.sch` – Proteus analog simulation
- `arduino_circuit.sch` – Proteus simulation with Arduino
- `ldr_control.ino` – Arduino source code

---

## 📌 Applications

- Smart room lighting
- Outdoor lighting automation
- Energy saving systems



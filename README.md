# 🌿 Smart Plant Monitoring System (Fully Analog)

A fully analog system designed to **automatically control irrigation, temperature, and lighting** for plant health without the use of any microcontroller or digital logic.

## 🛠️ Project Overview

This system uses **analog electronics** like sensors, comparators, op-amps, and transistors to create a sustainable and low-cost solution for plant monitoring and care. It is suitable for small indoor gardens and educational demonstrations.

## 🎯 Features

- 🌱 **Irrigation Control**  
  Activates a water pump when soil moisture drops below a set threshold.

- 🌡️ **Temperature Regulation**  
  Turns on a fan or ventilation system if ambient temperature rises too high.

- 💡 **Lighting Automation**  
  Controls artificial grow lights based on ambient light levels or day/night detection.

## 🔧 System Components

| Feature         | Component Used                        |
|----------------|----------------------------------------|
| Moisture Sensing  | Soil moisture sensor + Comparator       |
| Water Pump Driver | Transistor/BJT circuit with relay       |
| Temperature Sensing | Thermistor + Op-Amp Comparator         |
| Cooling Fan Driver | NPN transistor + Diode protection       |
| Light Sensing    | LDR (Light Dependent Resistor) + Comparator |
| Power Supply     | 12V DC / Regulated linear power supply   |

## ⚙️ How It Works

- **Soil Moisture**: When soil dries, voltage from the moisture sensor changes, triggering a comparator that turns on the water pump.
- **Temperature Control**: Thermistor senses heat. When the voltage across it reaches a threshold, it triggers the fan using a transistor.
- **Light Control**: LDR senses ambient light. If it's too dark, a comparator switches on the LED grow light using a relay.



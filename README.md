# Lineman_Safety_Monitoring_System

A real-time embedded safety solution to protect electrical linemen from accidental high-voltage exposure.

## 🔧 Built With
- Arduino UNO
- Voltage Detection Sensors
- GSM Module (SIM800L/SIM900)
- Embedded C
- Buzzer & LED Modules

---

## 📝 Project Description

The **Lineman Safety Monitoring System** enhances safety for electrical workers by detecting the presence of voltage on electric lines and warning the lineman using **auditory (buzzer)** and **visual (LED)** signals. In critical conditions, it can optionally **send SMS alerts** via a **GSM module** to notify emergency contacts or supervisors.

---

## ✅ Key Features

- 🔋 **Live Wire Detection**  
  Uses voltage sensors to identify the presence of high voltage before any physical contact.

- 🚨 **Emergency Alert System**  
  In unsafe conditions, a buzzer activates and optionally an **SMS is sent** using the GSM module.

- 📳 **Real-Time Alerts**  
  Immediate auditory and visual feedback helps the lineman make quick decisions.

- 🔒 **Safety First Approach**  
  Prevents workers from accessing live wires until confirmed safe.

- 📲 **Optional GSM Integration**  
  Sends automatic alerts to supervisors in case of voltage exposure.

- 🧠 **Arduino-Based Embedded Logic**  
  Simple and effective C code on Arduino to process sensor data and control output devices.

---

## 📂 Example Use Case

> A lineman connects the system to a power line before maintenance. The voltage sensor detects a high voltage.  
> 🔴 Red LED and buzzer are triggered.  
> ✅ Once power is shut off, the green LED turns on to indicate safety.  
> ⚠️ If voltage returns suddenly, an SMS alert is automatically sent via GSM.




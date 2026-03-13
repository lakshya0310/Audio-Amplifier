# 🎛️ Audio Amplifier – Electronics Workshop Project

**Course**: EC2.202 – Spring 2026   
**Goal**: Design and build an audio amplifier capable of driving a 10Ω load with ≥1.5W output power using a ±5V supply.

---

## 🔍 Project Overview

This project involves the design, simulation, and hardware implementation of a **multi-stage audio amplifier** that can amplify small microphone signals to speaker-level power while maintaining clarity and fidelity within the **audible frequency range (20 Hz – 20 kHz)**.

---

## ⚙️ Architecture & Stages

1. ### 🎤 Pre-Amplifier (Differential Amplifier)
   - Boosts low-level mic signals
   - Reduces noise and improves signal quality
   - High CMRR and input impedance

2. ### 📈 Gain Stage (Common Emitter Amplifier)
   - Provides significant voltage amplification
   - Introduces a 180° phase shift (inversion)
   - Drives the next filtering stage effectively

3. ### 🎚️ Band-Pass Filter
   - Passes only the 20 Hz – 20 kHz audio range
   - Removes noise and unwanted frequencies
   - Maintains unity gain within the passband

4. ### 🔊 Power Amplifier (Class-AB)
   - Delivers sufficient power to a 10Ω load
   - Ensures low distortion and higher efficiency
   - Final stage to drive speaker output

---

## 📦 Outcome

- **Simulated & tested successfully in LTSpice and hardware**
- Achieved >1.5W output power with clear audio reproduction
- Key focus on gain, frequency response, and minimal distortion

---

## 🛠️ Tools Used

- **LTSpice** – Circuit simulation  
- **Breadboard & Discrete Components** – Hardware prototyping  
- **Microphone & Speaker** – Audio I/O  
- **Oscilloscope & Function Generator** – Testing and validation

---

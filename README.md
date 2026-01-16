# Microphone Amplifier with Class AB Driver  
**EE2301 – Electronic Devices and Circuits Lab | Final Project**

## Overview
This project implements a complete **audio amplification chain** consisting of a **transistor-based pre-amplifier** followed by a **Class AB power amplifier**. The system amplifies low-level microphone or AUX input signals and safely drives an **8 Ω loudspeaker** with controlled distortion, good thermal stability, and reasonable efficiency.

The design was iteratively improved to address issues such as crossover distortion, overheating, and noise, resulting in a stable and reliable audio amplifier suitable for educational and experimental purposes.

---

## Features
- Two-stage **audio pre-amplifier** using BC547 transistors  
- **Class AB push-pull power amplifier** using TIP41C–TIP42C complementary pair  
- Reduced crossover distortion using diode biasing  
- Stable operation with emitter resistors for thermal control  
- Capable of driving an **8 Ω speaker**  
- Simulation-based evaluation of:
  - Gain and bandwidth
  - Total Harmonic Distortion (THD)
  - Signal-to-Noise Ratio (SNR)
  - Power Supply Rejection Ratio (PSRR)
  - Quiescent current
  - Output swing and output power

---

## Circuit Architecture
The amplifier consists of the following major blocks:

1. **Pre-Amplifier Stage**
   - High input impedance
   - High voltage gain
   - AC coupling to block DC offsets

2. **Driver Stage**
   - Prepares the signal for the power transistors
   - Ensures sufficient base drive

3. **Class AB Output Stage**
   - Complementary push-pull configuration
   - Diode biasing to minimize crossover distortion
   - Emitter resistors for current sharing and thermal stability

4. **Output Coupling**
   - Large capacitor to block DC to the speaker

---

## Tools Used
- **LTspice** (simulation)
- **LaTeX** for documentation
- **CircuitikZ** for schematic illustrations

---

## References
- Pre-amplifier design inspired by:  
  https://sound-au.com/project13.htm  
- Class AB amplifier reference:  
  https://www.electronics-tutorials.ws/amplifier/class-ab-amplifier.html  

---

## Author
**Bhavanisankar G S**  
EE24BTECH11012  
Department of Electrical Engineering  

---


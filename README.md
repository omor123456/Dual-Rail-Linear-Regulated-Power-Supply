# Dual-Rail-Linear-Regulated-Power-Supply


Hands-on power supply design and validation using a transformer, rectifier, linear voltage regulators, LTspice, and an oscilloscope.

---

### Overview

Designed and analyzed positive and negative linear voltage regulator circuits that convert an AC transformer output into regulated DC power.

The project explored the complete power conversion path:

    AC Transformer
          ↓
    Bridge Rectifier
          ↓
    Smoothing Capacitors
          ↓
    Linear Regulator
          ↓
    Regulated DC Output

The positive and negative regulator configurations were investigated to understand how regulated dual-polarity supplies can provide power for analog circuits such as operational amplifiers and other signal-processing circuitry

<img width="946" height="364" alt="image" src="https://github.com/user-attachments/assets/56e363bc-3371-4530-af35-6b5b53b46389" />


---

### Applications

Dual-rail regulated power supplies are commonly used to provide positive and negative supply rails for:

• Operational amplifier circuits  
• Analog signal-processing systems  
• Audio electronics  
• Instrumentation circuits  
• Sensor interfaces  
• Analog test and measurement equipment  

Having both positive and negative rails is especially useful for analog circuits that need signals to swing above and below ground.

---

### Hardware Testing

Built and tested the regulator circuits using a transformer, bridge rectifier, smoothing capacitors, potentiometer, and linear voltage regulators.

Used an oscilloscope to compare the unregulated rectified waveform with the regulated DC output and observe the reduction in voltage ripple after the regulator stage.

The hardware testing provided practical experience with:

• Transformer AC output  
• Full-wave rectification  
• Capacitor smoothing  
• Linear voltage regulation  
• Output voltage adjustment  
• Oscilloscope waveform analysis  
• Power-supply polarity and measurement

---

### LTspice Simulation

Simulated the regulator circuits in LTspice before hardware testing to study the behavior of the positive and negative voltage regulation stages.

The simulations were used to examine the regulated output and understand how the circuit responds to different operating conditions.

LTspice files for the positive and negative regulator circuits are included in the repository.

---

### Circuit Schematics

Positive Voltage Regulator

<img width="1160" height="380" alt="image" src="https://github.com/user-attachments/assets/427e037f-8586-4924-9bfd-3c0e17c0291f" />


Negative Voltage Regulator

<img width="1214" height="382" alt="image" src="https://github.com/user-attachments/assets/50ae2f27-97bc-4ca7-b043-331dde359917" />


Ideal schematics for both negative and positive power supply under one circuit

<img width="2552" height="1248" alt="image" src="https://github.com/user-attachments/assets/ce424b4d-854c-4efd-a641-ffbba8aef636" />


---

### Oscilloscope Analysis

Compared the unregulated input waveform with the regulated output waveform using an oscilloscope.

This allowed the effect of the rectifier, smoothing capacitors, and linear regulator to be observed directly in hardware.


---

### Engineering Workflow

    Transformer AC Output
            ↓
      Bridge Rectifier
            ↓
     Capacitor Filtering
            ↓
     Unregulated DC
            ↓
     Linear Regulation
            ↓
      Regulated DC
            ↓
     Oscilloscope Validation

---

### Tools & Equipment

LTspice  
Circuit simulation and analysis

Oscilloscope  
Waveform and ripple measurement

Transformer  
AC voltage source and isolation

DMM  
DC voltage measurement

Breadboard  
Hardware implementation and testing

---

### Skills Demonstrated

Power Electronics  
Linear Voltage Regulators  
AC-to-DC Conversion  
Bridge Rectification  
Capacitor Filtering  
Positive & Negative Voltage Rails  
LTspice Simulation  
Oscilloscope Measurement  
Waveform Analysis  
Analog Circuit Testing



Worked on the positive voltage regulator inside the EE lab:

<img width="300" height="320" alt="image" src="https://github.com/user-attachments/assets/dcb98fc8-9676-4ab2-8483-943285582833" />


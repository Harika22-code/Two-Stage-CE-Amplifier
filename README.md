# Two-Stage Common Emitter Amplifier

This project features a two-stage Common Emitter (CE) amplifier designed for high-gain audio or signal processing applications. By cascading two CE stages, the circuit achieves significant voltage amplification while maintaining the characteristic 180° phase shift per stage (resulting in a 360° or 0° total shift).

This project focuses on overcoming typical BJT limitations like thermal runaway and β sensitivity through architectural improvements.

---

##  Key Design Features

- **Voltage Divider Biasing**  
  Ensures a stable Q-point, making the circuit independent of β variations between different transistors.

- **Emitter Swamping**  
  Utilizes partially bypassed emitter resistors to provide negative feedback, stabilizing gain and increasing input impedance.

- **Thermal Stability**  
  Designed to mitigate internal resistance fluctuations ($r_e'$) and temperature-induced drift.

- **Capacitive Coupling**  
  Input, output, and inter-stage coupling capacitors are used to isolate DC biasing while maintaining a clean AC signal path.

---

##  Performance Specifications

| Parameter | Value |
|----------|------|
| Gain of I stage (A1) | 15 |
| Gain of II stage (A2) | 30 |
| Load resistance (RL) | 2.2kΩ |
| Bandwidth (-3dB) | 20Hz – 20kHz |
| Range of β | 100 – 200 |
| Supply Voltage (Vcc) | 12V |

---

##  Notes
- Total Gain ≈ A1 × A2 = 15 × 30 = **450**
- Suitable for audio-frequency amplification

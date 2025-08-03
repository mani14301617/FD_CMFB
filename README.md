# Fully Differential Amplifier with Common-Mode Feedback (CMFB)

This project implements a **Fully Differential Operational Transconductance Amplifier (OTA)** with integrated **Common-Mode Feedback (CMFB)** to stabilize the output common-mode voltage. The design includes circuit schematics, simulation results, and a common-centroid layout.

## 🧑‍💻 Contributors

- Manikanta Krishnamurthy – 220102059  
- Bhavik Jain – 220102023  

---

## 🧠 Key Concepts

- **Fully Differential Amplifier**: Offers improved power supply rejection and noise immunity.
- **CMFB (Common-Mode Feedback)**: Ensures that the output common-mode voltage stays within a desired range, critical for proper differential amplifier operation.
- **OTA (Operational Transconductance Amplifier)**: Used in analog signal processing; output current is proportional to differential input voltage.

---

## 🔧 Design Parameters

| Parameter              | Value         |
|------------------------|---------------|
| Gain                   | 40 dB         |
| Tail Current           | 10 µA         |
| NMOS Width             | 2 µm          |
| PMOS Width             | 8 µm          |
| Bandwidth              | 200 kHz       |
| Input Voltage Range    | 0.785V – 1.66V|
| Technology             | L = 900 nm    |
| gm/Id Design Target    | 10            |

---

## 🧪 Simulation Results

- **Phase Response**:  
  - 180° phase difference → Gain = **40 dB**  
  - 0° phase difference → Gain = **-75 dB**

- **Step Response**:  
  - **Settling Time**: 500 ns

---

## 🖼️ Layout

- Implemented using **Common-Centroid Layout** technique to minimize mismatch.
- Layouts available for:
  - OTA core
  - CMFB circuitry
<img width="770" height="676" alt="Screenshot 2025-04-22 142707" src="https://github.com/user-attachments/assets/2fb105e4-e741-4d00-837e-5ee6795960dc" />

---

## ✅ Future Work

- Integration with larger analog signal chains (e.g., ADC front-ends).
- Layout optimization for area and parasitics.
- Monte Carlo simulations for mismatch analysis.

---

## 📜 License

This project is for academic and educational use. Please cite the contributors when referencing or building upon this work.


# Underwater-CS
# Underwater Digital Communication Using Infrared Signals

### 👩‍🔬 A Final Year Major Project by Shruti Singh, P. Himanshu Rao, and Rahul Pandey  
**B.Tech in Electronics & Telecommunication Engineering**  
Government Engineering College, Raipur (Session: 2024–2025)

---

## 📘 Project Overview

This project demonstrates a **low-cost, microcontroller-based underwater communication system** using **infrared (IR) signals**. It focuses on transmitting **numerical data** between two modules submerged in a water medium, using **IR LED** on the transmitter and **TSOP1738 IR receiver** on the receiver.

---

## 🎯 Objectives

- Develop a **working prototype** of underwater IR communication.
- Explore **data transmission feasibility** in water using optical IR methods.
- Enable basic user input (increment/decrement values) and **real-time display**.
- Provide a **cost-effective and educational model** for underwater communication.

---

## 🔧 Hardware Used

- ATmega328 Microcontroller (Transmitter & Receiver)
- IR LED (940nm)
- TSOP1738 IR Receiver
- 16x2 LCD Display with I2C interface
- Push Buttons for user input
- LM2596 Buck Converter (Power regulation)
- 9V Battery

---

## 💻 Software Tools

- **Arduino IDE** (Coding)
- Embedded C (Arduino Syntax)
- Libraries: `LiquidCrystal_I2C`, `Wire.h`

---

## 📡 Working Principle

1. **Input Selection**: User selects a number using push buttons.
2. **IR Transmission**: Transmitter encodes data as IR pulses (1 pulse = +1, 11 pulses = -1).
3. **Medium Simulation**: Data is passed through water using a transparent container.
4. **Reception**: TSOP1738 receives and decodes the signal.
5. **Output**: Received number is displayed on LCD.

---

## 🧪 Experimental Results

| Environment            | Success Rate | Max Range | Delay     |
|------------------------|--------------|-----------|-----------|
| Dry-air (Lab)          | 100%         | 1.5 m     | <0.5 sec  |
| Still Water            | ~90%         | 20-30 cm  | ~1 sec    |
| Turbid Water           | ~60%         | 10-15 cm  | ~1.5 sec  |
| Mild Saline Water      | ~70%         | 15-20 cm  | ~1.2 sec  |
| Foggy Air              | ~85%         | 80-100 cm | ~0.8 sec  |

---

## 📈 Future Enhancements

- Two-way (full-duplex) communication
- High-power IR LEDs for range expansion
- Waterproof enclosures
- CRC/Error detection protocols
- Integration with AUVs or diver systems

---

## 📚 References

- [IJEDR.org](http://www.ijedr.org)
- IEEE Communications Surveys
- Research by Shen et al., Zhang et al., Wang et al.

---

## 🧠 Authors

- **Shruti Kumari Singh** – Roll No. 301602821051
- **P Himanshu Rao** – Roll No. 301602821032
- **Rahul Pandey** – Roll No. 301602821011

Supervised by: **Mrs. Vinita Sahu**, Assistant Professor  
Department of Electronics & Telecommunication  
Government Engineering College, Raipur

---

## 🏷️ Tags

`#IR Communication` `#Underwater System` `#ATmega328` `#Electronics Project` `#Optical Communication` `#Infrared Signals`

---

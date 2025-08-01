# 🌈 Color Cycle LEDs – ESP32 LED Sequencer

This project cycles 5 different colored LEDs connected to an ESP32 in a custom blinking pattern.


## 🔌 GPIO Pin Mapping

| LED Color | GPIO Pin | ESP32 Label | Resistor | Notes                    |
|-----------|----------|-------------|----------|--------------------------|
| Red       | GPIO 2   | G2          | 220Ω     | Anode (+) to GPIO pin    |
| Yellow    | GPIO 4   | G4          | 220Ω     |                          |
| Green     | GPIO 5   | G5          | 220Ω     |                          |
| Blue      | GPIO 15  | G15         | 220Ω     |                          |
| White     | GPIO 18  | G18         | 220Ω     |                          |

---

## 🛠️ Setup Instructions

1. Insert 5 LEDs into the breadboard.  
2. Connect a **220Ω resistor** from each ESP32 GPIO pin to the **anode (+)** leg of the LED.  
3. Connect all LED **cathodes (–)** together to the **GND rail** on the breadboard.  
4. Connect the breadboard **GND rail** to an ESP32 **GND pin**.  
5. Connect the ESP32 to your computer via USB and upload the provided sketch using Arduino IDE.  
6. Watch the LEDs blink in a colorful sequence.

---

## 📁 Files Included

- Your Arduino sketch file (e.g., ColorCycle.ino)  
- .gitignore, LICENSE, README.md

---

## 📃 License

MIT License — free to use, modify, and share.

---

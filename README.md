# RideSentry: Intelligent Bike Weight Detection System

RideSentry is a safety-focused project designed to detect overloading on two-wheelers using a Load Cell, HX711 amplifier, and an Arduino microcontroller. This system issues alerts when unsafe weight is detected to help prevent accidents.

## 🚀 Features
- Real-time load sensing
- Buzzer alert on overload
- Portable and low-cost

## 🔧 Technologies Used
- Arduino UNO
- HX711 Load Cell Amplifier
- Load Cell Sensor
- Buzzer
- Embedded C (Arduino IDE)

## 📂 Project Structure
- `code/`: Arduino code for sensor readings and alert system
- `schematics/`: Circuit diagrams and wiring
- `docs/`: Supporting documents (e.g., report PDF)
- `images/`: Prototype photos and screenshots

## 📷 Circuit Preview
![Circuit Diagram]![image](https://github.com/user-attachments/assets/43287687-73f8-40e6-b3a1-a6120dbeb814)


## 📄 How It Works
1. Load cell measures the weight on the bike seat.
2. HX711 amplifies the analog signal and passes it to the Arduino.
3. If the detected weight crosses a safe threshold, the buzzer triggers.

## 📜 License
This project is open source and available under the MIT License.

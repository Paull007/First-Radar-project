# 🚀 Ultrasonic Distance Measurement with Arduino  

This project uses an **Arduino Uno** and an **HC-SR04 ultrasonic sensor** to measure distances and provide visual feedback via LEDs. The sensor readings are displayed in the **Serial Monitor**, while two LEDs blink alternately as the detected distance decreases. A power module is also included for external power supply.  

## 🛠 Features  
- ✅ Ultrasonic distance measurement using **HC-SR04**  
- ✅ LED indication based on proximity  
- ✅ Real-time distance readings in the **Serial Monitor**  
- ✅ Efficient timing using `millis()` instead of `delay()`  
- ✅ Simple and lightweight code  

## 🔧 Hardware Requirements  
- **Arduino Uno**  
- **HC-SR04 Ultrasonic Sensor**  
- **2 LEDs + Resistors**  
- **Breadboard & Jumper Wires**  
- **External Power Module (optional)**  

## 📜 Usage  
- Upload the provided code to your **Arduino Uno**.  
- Connect the **HC-SR04** sensor to the appropriate pins:  
  - **Trig → D9**  
  - **Echo → D10**  
- Connect the LEDs to digital pins (e.g., **D6 & D7**) via resistors.  
- Power up the circuit using **USB or an external power supply**.  
- Open the **Serial Monitor** to observe the real-time distance readings and LED behavior.  

📌 *Refer to the circuit diagram for proper wiring.*  

<img src="https://github.com/user-attachments/assets/fe485489-b3a8-4b05-a655-0e4afe73b9ff" width="400" />

## Also here are pictures with it irl.
<img src="https://github.com/user-attachments/assets/ea46dc4e-ee89-4ff2-bb1d-46e58f134fe3" width="300" /> <img src="https://github.com/user-attachments/assets/c0b7ecde-fa93-432f-9237-374983b127d4" width="350" />

## Quick demonstration video.



https://github.com/user-attachments/assets/0f454828-4167-40cf-9d17-bcf5189860ca


# **Sensor to correct body posture and regulate viewing distance**

## **Overview**
This project promotes better ergonomic habits by monitoring the **distance between a user's face and their laptop** screen. If the user's face is detected to be within **30 cm**, a buzzer sounds to alert them to adjust their position. The system uses an **ultrasonic sensor** to continuously track the distance and a **buzzer** to provide real-time feedback. The system is easily extendable with additional sensors, such as a **flex sensor**, to enhance posture monitoring.

---

## **Features**
- **Distance Monitoring**: Tracks the distance between the user's face and the laptop screen using an **ultrasonic sensor**.
- **Buzzer Alert**: A buzzer sounds if the user's face is detected within **30 cm** of the screen, encouraging them to sit back for better ergonomics.
- **Flexible Sensor Integration**: Includes the option to connect additional sensors, such as a **flex sensor**, for more ergonomic feedback (e.g., tracking seating posture).
- **Customization**: Use an **analog-to-digital converter (ADC)** for further sensor integration, making the system adaptable for various ergonomic needs.

---

## **Components**
1. **Ultrasonic Sensor (HC-SR04)**: Measures the distance between the user and the laptop.
2. **Buzzer**: Provides an audible alert when the user is too close to the screen.
3. **Flex Sensor (optional)**: Can be added to monitor body posture (e.g., slouching).
4. **Microcontroller (e.g., Raspberry Pi Pico)**: Manages sensor data and triggers the buzzer.
5. **Switch**: Used to enable/disable the buzzer manually.

---
## **Usage Instructions**

1. **Power the Circuit**: 
   - Connect the microcontroller to a power source (USB or battery).
  
2. **Distance Monitoring**:
   - The system starts monitoring the distance between the user’s face and the laptop immediately after powering on.
   - If the user's face comes within **30 cm** of the screen, the **buzzer will sound**, reminding the user to sit back.

---

## **Conclusion**
This system helps promote better **posture** and **ergonomics** by giving users **real-time feedback** when they sit too close to their laptop screens. By using simple components and customizable code, this project provides an effective and low-cost solution for **encouraging healthy computing habits**.

---

## **Future Enhancements**
1. **Additional Sensors**:
   - Integrate more sensors to track additional aspects of ergonomics, such as detecting poor seating posture using the **flex sensor**.
   
2. **Smart Alerts**:
   - Implement more sophisticated feedback mechanisms such as **vibration motors** or **visual indicators** (LEDs) for less intrusive notifications.
  
3. **Data Logging**:
   - Add data logging to track user behavior over time and analyze ergonomic trends.

---

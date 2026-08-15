#     🔔USER-CONFIGURABLE-MEDICINE-REMINDER-SYSTEM 🔔
## 🔖Project Overview
This project is designed with LPC2148 ARM7 microcontroller,aims to help and assist elderly people and patients who need regular medicine reminders. 

The system is equipped with a Real-time Clock(RTC) to monitor the date and time correctly. It can handle upto three medicine reminders which can be configured using the 4x4 matrix keyboard. The 16x2 LCD display and buzzer alert the user when its time to take the medicine.
## 🎯Objectives
- Configure three medicine schedules
- Display current date and time using RTC
- Allow users to edit RTC settings
- Compare RTC time with medicine timings
- Generate medicine reminders
- Provide a keypad-driven user interface
- Stop reminder using EINT1
- Automatically stop reminder after one minute

## ✨Features
- Real-Time Clock Integration
- Multiple medicine Reminders
- Menu driven user interface
- Smart Alert System
- Audio-Visual Notification
- External Interrupt-based configuration
## ✏️Block diagram
<img width="793" height="457" alt="image" src="https://github.com/user-attachments/assets/7b04f83c-698b-41ed-8191-5743c03cff9c" />

## ⚡Circuit Diagram
<img width="1065" height="730" alt="x1" src="https://github.com/user-attachments/assets/f377bed4-3bf1-4a99-8995-7f671e7b23e2" />

## Components
| Component | Description |
|------------|-------------|
| RTC Module | Real-Time Clock |
| 16×2 LCD | Display |
| 4×4 Matrix Keypad | User Input |
| Buzzer | Reminder Alert |
| Push Button (EINT0) | Configuration Mode |
| Push Button (EINT1) | Reminder Acknowledgment |

---

## ⌨️Software Requirements
- Keil uvision
- Flash magic
## Hardware Description
### Pin Description
| Peripheral |  Pin |
|------------|-------------|
| LCD Data | P0.8 – P0.15 |
| LCD RS | P0.16 |
| LCD RW | P0.17 |
| LCD EN | P0.18 |
| Buzzer | P0.0 |
| EINT0 | P0.1 |
| EINT1 | P0.3 |
| Keypad Rows | P1.16 – P1.19 |
| Keypad Columns | P1.20 – P1.23 |

---
### RTC Clock
<img width="939" height="295" alt="image" src="https://github.com/user-attachments/assets/133662f6-fdb0-424a-8347-a2c23cc44279" />

### Main Menu
<img width="995" height="347" alt="image" src="https://github.com/user-attachments/assets/09e6ddf4-b3f2-44bd-8d4e-3712f77e52ff" />

### Reminder on LCD
<img width="1001" height="424" alt="image" src="https://github.com/user-attachments/assets/89be8935-b85d-40d4-af19-44d37855a10d" />

## 🧰Working principle
- RTC is intialized and continuously maintains current time
- Switch 1 is pressed by user to enter user mode
- User sets the reminder user the keypad
- LPC2148 stores and compares RTC time with reminder time
- When the time matches the buzzer goes off and a notification is displayed on the LCD
- User presses switch 2 to stop the reminder
- System returns to normal monitoring mode
## 🔨Applications
- Medicine reminder systems
- Hospital Alert monitors
- Elderly Consumers 
## ⌛Future Enhancements
- Mobile based Application
- GSM based SMS alerts
- Multiple user Support
-  Voice reminders
## Developed by
Md. Hassaan Ali Areeb | ECE | Embedded Systems Enginner



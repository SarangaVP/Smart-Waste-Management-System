# Smart-Waste-Management-System
This project implements a fully automated waste management system, developed as part of the Electrical Measurements and Instrumentation module. It processes sensor inputs and controls actuators to classify and sort waste based on multiple sensor readings. The system uses LabVIEW, interfaced through the NIDAQmx Data Acquisition System, and integrates a Rigol programmable DC supply for precise control signals.

The system classifies waste into metal, dry, and wet categories using sensor inputs. It automatically opens the bin when a person approaches and monitors the bin fill level using a custom-developed analog IR sensor, locking the lid once the bin is full.

Key sensors include an inductive proximity sensor to detect metal, an analog IR sensor for fill level measurement, and a soil moisture sensor to distinguish between dry and wet waste. Additionally, an IR sensor is used for proximity detection to automatically open the bin when a person approaches.

Servo motors controlled by a 555 timer circuit move the sorting mechanism based on sensor readings. The system detects the waste type, directs it to the correct bin, opens the lid when needed, and locks it when full to prevent overfilling.

LabVIEW is used for overall system control, while the NIDAQmx DAQ system handles sensor data and actuator control. The Rigol DC supply ensures accurate control signals throughout the system.

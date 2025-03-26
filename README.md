# Automated-Vehicle-Classification-Gating-System-and-Slot-Identification-Project
This project integrates an automated vehicle classification system with a smart parking slot identification mechanism. It uses computer vision and machine learning to detect vehicle types and manage gated entry. Additionally, it identifies parking slot availability in real-time using an image processing approach. The system is designed to enhance smart parking management and access control applications.

## **Key Features**  
✅ **Vehicle Classification** – Identifies six vehicle types: **Motorbike, Three-wheelers, Cars, Van, Bus, and Truck**.  
✅ **Automated Gating System** – **ESP32-CAM** detects vehicle type and opens the relevant parking gate.  
✅ **Parking Slot Identification** – Uses an image vision system to determine occupied and vacant slots.  
✅ **Real-Time Monitoring** – Continuously processes camera feed for instant decision-making.  

## **Technologies Used**  
- **Python, OpenCV, TensorFlow/Keras** – For training and implementing the vehicle classification model.  
- **ESP32-CAM** – For real-time vehicle identification and gate control.  
- **SolidWorks** – Used to design mechanical components.  
- **Revit & Twinmotion** – Created a 3D environment for system visualization.  

## **Implementation Details**  
- A **machine learning model** was trained to classify **six different vehicle types**.  
- **ESP32-CAM** captures images, processes them, and determines vehicle type.  
- Based on classification, the **relevant parking gate opens automatically**.  
- Parking slot availability is determined using an **image processing-based slot identification system**.  

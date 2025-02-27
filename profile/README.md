# **Project Purpose: AI-Driven Visual Servoing for Interactive Communication**  

## **Project Overview**  
This project aims to develop an **AI-powered interactive communication system** that utilizes **computer vision, motor control, and visual servoing** to interpret human hand gestures and control a motorized camera system. The system is divided into two interconnected components:  

1. **Master System**:  
   - Captures and tracks human hand movements using a camera.  
   - Uses AI-based gesture recognition to infer motion commands.  
   - Sends movement commands to the slave system.  

2. **Slave System**:  
   - Receives motion commands from the master system.  
   - Controls a motor that adjusts the camera’s position accordingly.  
   - Detects and identifies objects in the scene.  

This setup enables seamless, real-time interaction between a human operator and a remote-controlled camera system, with applications in **robotics, assistive technology, and human-machine interaction**.  
![image](https://github.com/user-attachments/assets/bfe639a4-54d1-4750-9769-ea94bac860b4)

---

## **Project Activities**  

| **Module**           | **Activity**                                      | **Owner**        |
|----------------------|--------------------------------------------------|------------------|
| **Hardware**         | Create motor driver | Victor |
| **Hardware**         | Create camera driver       | Victor |
|         **AI/ML**        | Design AI model for gesture inference | Alessandro |
|            **AI/ML**     | Design AI model for object detection | Alessandro |
|            **AI/ML**     | Create AI pipeline for training and testing | Alessandro |
|            **AI/ML**     | Model Camera in Isaac Sim | Alejandro |
|            **AI/ML**     | Create AI pipeline for generating synthetic data | Alejandro |
|            **Software**     | Deploy NN in camera hardware | Victor |
| **Vision**         | Implement estimation pose algorithm | Victor |
|  **Control**                | Implement master-slave communication protocol  | Alejandro |
|  **Control**                | Implement control manager to sync information | Alejandro |




### Our documentation to create python repositories [here](https://github.com/Laurel-Leaf-Labs/documentation)

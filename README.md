# ASL Hand Gesture Recognition using MediaPipe

## 
Project Overview
This project is an experimental attempt to **recognize American Sign Language (ASL) hand gestures** using **MediaPipe Hand Landmarks** and **OpenCV**.

The system detects hand landmarks in real time through a webcam and applies **rule-based logic** to classify hand poses into selected ASL letters. The project focuses on understanding **computer vision**, **hand tracking**, and **gesture recognition concepts** rather than producing a fully accurate ASL translation system.

---

## Objectives
- Explore real-time hand landmark detection using MediaPipe  
- Implement basic ASL letter recognition using rule-based logic  
- Visualize hand skeletons and landmarks  
- Understand the limitations of static gesture recognition  

---

## Technologies Used
- Python  
- OpenCV  
- MediaPipe (Hand Landmarker)  

---

## Project Constraints
This project has several limitations due to its current design and scope:

- The recognition system is **rule-based**, not machine-learning-based, which limits accuracy.
- Only **static hand poses** can be partially recognized.
- **Dynamic ASL letters (such as J and Z)** require motion tracking and are not fully supported.
- The system processes gestures frame-by-frame and does **not track motion over time**.
- Accuracy is affected by **camera quality, lighting conditions, and hand orientation**.
- The project uses a **standard webcam**, which is insufficient for precise motion and depth detection.

Because ASL involves **complex finger angles, depth, and continuous motion**, this approach alone is not enough for complete and reliable recognition.

---

## Current Status
- Partial recognition of selected ASL letters  
- Skeleton and landmark visualization implemented  
- Designed as a **prototype / learning project**

---

## Future Improvements
This project is planned to be improved in the future by:
- Using **specialized hardware** (e.g., depth cameras, motion sensors, or gloves) for better motion tracking
- Implementing **temporal analysis** for dynamic gestures
- Applying **machine learning or deep learning models** for accurate ASL classification
- Expanding support to full A–Z ASL recognition
- Adding confidence scores and gesture smoothing
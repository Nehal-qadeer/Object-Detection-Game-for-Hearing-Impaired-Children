# 🎮 Object Detection Game for Hearing-Impaired Children

> **An interactive educational tool using AI to bridge the communication gap through visual recognition.**

---

## 🌟 Project Purpose
This project was developed to help children with hearing impairments learn and identify objects in their surroundings through an engaging "Detection Game." 

Unlike standard detection tools, this is built as a **game** where the AI:
1. **Scans** the live environment using a webcam.
2. **Identifies** objects based on saved trained models.
3. **Displays** the names clearly on the screen to provide visual reinforcement for users who cannot rely on audio cues.

## 🚀 Technical Features
* **Live Detection:** Real-time object recognition using a custom **YOLOv8** model.
* **CPU Optimized:** Integrated with **Intel OpenVINO** to ensure smooth gameplay on standard laptops without needing a GPU.
* **Interactive UI:** A user-friendly desktop interface built with **PyQt6**.
* **Learning Reinforcement:** Provides immediate visual labels upon detection, making it an effective educational aid.

## 🛠️ Tech Stack
* **Programming:** Python 3.10+
* **AI Framework:** Ultralytics (YOLOv8)
* **Optimization:** OpenVINO Toolkit (for 25+ FPS on CPU)
* **Graphics/UI:** PyQt6 & OpenCV

## 📂 How the Game Works
* **Step 1:** The child points the camera at an object.
* **Step 2:** The AI detects the object from its saved library of trained models.
* **Step 3:** The game "captures" the object and displays the name in a large, easy-to-read font.

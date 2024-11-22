# Jellyfish Detection and Alert System

## Background Information
Jellyfish-related accidents at beaches are a recurring and significant safety issue every year. Jellyfish are commonly found in oceans, but systems for detecting their presence in real-time are still lacking. To prevent jellyfish stings, a fast and accurate detection system is essential. This project aims to develop a system that detects the appearance of jellyfish at beaches and sends alerts to people, helping to prevent accidents and ensuring safer marine activities for everyone.

---

## General Description of the Current Project
This project aims to develop a system that detects jellyfish in real-time at beaches and immediately alerts users about their location. The system uses a YOLOv5-based model to detect jellyfish and streams real-time footage of the beach area through cameras. The detected jellyfish’s location information is sent as a warning message to the administrator, and alerts can also be delivered to users through a mobile app. This initiative seeks to prevent jellyfish-related accidents by providing timely warnings, minimizing risks, and promoting safety.

---

## Proposed Idea for Enhancements to the Project
There are several ways this project can be strengthened to improve jellyfish detection accuracy and speed:

- **Drone Usage**: Drones could be employed to detect jellyfish over a larger area in real-time, offering wider coverage.
- **Improvement in Deep Learning Models**: Enhance the performance of deep learning models to better distinguish jellyfish from other similar marine creatures.
- **Mobile App Functionality**: Expand the mobile app to provide real-time jellyfish alerts and information to beachgoers, allowing them to respond faster and stay safe.

---

## Value and Significance of this Project
This project offers a significant technological solution for societal safety. A real-time jellyfish detection and warning system can prevent accidents at beaches, making a revolutionary impact on marine safety. Moreover, by developing technology that accurately detects marine life, the project can raise awareness of marine ecosystems and contribute to environmental conservation. Through this system, beach managers can proactively prevent accidents, and users can enjoy their ocean activities in a safer environment.

---

## Current Limitations
This project faces several limitations:

1. **Detection Accuracy**: The accuracy of jellyfish detection is not perfect, and distinguishing jellyfish from other marine life remains challenging.
2. **Real-Time Video Streaming**: Potential delays in video streaming can occur due to network conditions or camera quality.
3. **Camera Performance**: Camera performance may be affected by weather conditions or water turbidity, reducing the effectiveness of the detection system.

To overcome these challenges, improvements in model performance and hardware upgrades are needed.

---

## Literature Review
Previous research has proposed various methods for jellyfish detection, but there is a lack of studies on real-time detection and alerting systems. Most studies have used underwater cameras or drones, and some deep learning-based jellyfish detection models exist. In particular, studies using YOLOv5 for real-time jellyfish detection have been conducted, but they faced challenges in terms of accuracy and speed in real-world environments. This project aims to improve the accuracy of jellyfish detection and implement a real-time alert system, addressing the limitations of previous research.

---

## Data Visualizations

### 1. Labels & 2. Labels Correlogram
<p align="center">
  <img src="https://github.com/user-attachments/assets/27c1308f-07ae-4703-9407-d22c6897b4be" alt="labels" width="300"/>
  <img src="https://github.com/user-attachments/assets/478687eb-f6b6-404f-af2b-70c8502c5e74" alt="labels_correlogram" width="300"/>
</p>

### 3. Validation Batch 0 - Labels & 4. Validation Batch 0 - Predictions
<p align="center">
  <img src="https://github.com/user-attachments/assets/4a2c70a6-09f8-49b4-b8d5-bddaaab9c36c" alt="val_batch0_labels" width="300"/>
  <img src="https://github.com/user-attachments/assets/ae2b271a-8a07-4526-82ff-29fecf9ae289" alt="val_batch0_pred" width="300"/>
</p>

### 5. Validation Batch 1 - Labels & 6. Validation Batch 1 - Predictions
<p align="center">
  <img src="https://github.com/user-attachments/assets/9634f787-ced8-4e47-90a9-411d1d5b18d3" alt="val_batch1_labels" width="300"/>
  <img src="https://github.com/user-attachments/assets/9f7dacb5-a7d0-4462-9249-99ec6cf3e107" alt="val_batch1_labels" width="300"/>
</p>

---

## Project Video
<div style="display: flex; justify-content: space-between; width: 100%; margin-top: 20px;">
    <a href="https://drive.google.com/file/d/18E-5xXRYZZ5nzAA-YYjmXNJ7a-u6IUwB/view?usp=drive_link" target="_blank" style="background-color: #4CAF50; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none;">Watch Video 1</a>
    <a href="https://drive.google.com/open?id=12jKLmn8C3fWC_U2AkMMDxTs9iM72wZn3&usp=drive_copy" target="_blank" style="background-color: #2196F3; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none;">Watch Video 2</a>
    <a href="https://drive.google.com/open?id=1MI4fqwzlUtSfHMZNHySFKgDN5rTygjxP&usp=drive_copy" target="_blank" style="background-color: #f44336; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none;">Watch Video 3</a>
</div>

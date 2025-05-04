# 🚗 Autonomous Vehicle Perception System

An end-to-end Perception System that analyzes driving scenes from both images and videos.  
Integrates multiple Computer Vision models to perform **Object Detection**, **Road/Lane Segmentation**, and **Depth Estimation**.  
Supports real-world dashcam datasets as well as videos captured around vehicles.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Tesla_Model_3_autopilot_sensors.jpg/800px-Tesla_Model_3_autopilot_sensors.jpg" width="500" alt="Autonomous Perception"/>
</p>

> **Example Output:**  
> - Detected Vehicles and Pedestrians  
> - Segmented Road and Lane Layout  
> - Estimated Depth Map (distance calculation)

---

## 🚀 Features

- Unified Perception Pipeline handling both images and videos.
- Supports YOLOv8 Object Detection + Segmentation + MiDaS Depth Estimation.
- Preprocessing and Cleaning of datasets (removing corrupt/broken files).
- Video frame extraction for unified frame-based processing.
- Visualization of detection, segmentation, and depth side-by-side.
- Modular design → Easily extensible for new perception tasks.

---

## 📚 Datasets

- [100K Vehicle Dashcam Image Dataset](https://www.kaggle.com/datasets/mdfahimbinamin/100k-vehicle-dashcam-image-dataset)
- [Videos Around Cars Dataset](https://www.kaggle.com/datasets/tapakah68/videos-around-cars)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/autonomous-vehicle-perception.git
cd autonomous-vehicle-perception

# Underwater Object Detection using YOLO11

This repository contains the code implementation for our research paper:**"Underwater Object Detection using YOLO11 Architecture"**

Authors: Srushti Kamble, Riya Khatod, Shreyas Kumbar, Darshan Ghatge, Dr. Uday Kulkarni, Sneha Varur  
Affiliation: School of Computer Science and Engineering, KLE Technological University, Hubballi, India  
Published in: 3rd International Conference on Futuristic Technologies (INCOFT-2025), 21–22 February 2025  

📄 [Read the full paper](Underwater_object_detection.pdf)

---

## 📄 Abstract
Low visibility, noise, and changing object scales all pose substantial hurdles to underwater object detection, limiting the performance of typical detection techniques. This paper introduces YOLO11, an enhanced object detection framework developed to address these issues. The suggested system improves detection accuracy in challenging underwater environments by combining unique strategies such as lightweight attention mechanisms and multi-scale feature fusion. To address the scarcity of labeled datasets, the method employs transfer learning and synthetic data augmentation, ensuring robust generalization across a variety of circumstances. Experimental results show that YOLO11 obtains a precision of 80.4%, recall of 71.1%, and mAP50 of 76.1%, beating earlier models like YOLOv5, YOLOv8 and YOLOv9. Furthermore, YOLO11 has excellent real-time processing capabilities, making it ideal for applications such as environmental surveillance, marine life monitoring, and autonomous underwater vehicles.

---

## 📊 Results

| Model  | Precision | Recall | mAP50 | mAP50-95 |
|--------|-----------|--------|-------|----------|
| YOLOv5 | 0.746     | 0.637  | 0.709 | 0.366    |
| YOLOv8 | 0.807     | 0.657  | 0.732 | 0.436    |
| YOLOv9 | 0.805     | 0.662  | 0.737 | 0.475    |
| **YOLO11** | **0.804**     | **0.711**  | **0.761** | **0.458**    |

---

## 📂 Files
- `underwater_object_detection.ipynb` — Main Jupyter Notebook containing the code and experiments.
- `LICENSE` — MIT License file.
- `README.md` — Project description and documentation.
- `Underwater_object_detection.pdf` — Full conference paper.

---

## 🔧 Requirements
To install dependencies:
```bash
pip install opencv-python numpy matplotlib torch torchvision

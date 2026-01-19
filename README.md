# 🌫️ YOLO-Based Object Detection in Foggy Environments

This project implements a **YOLO-based object detection system** designed to detect people in **foggy and low-visibility environments**.  
It focuses on **real-world deployment practices**, keeping the repository lightweight and professional by excluding large models and datasets.

---

## 🚀 Features

- YOLO-based object detection
- Optimized for foggy / low-visibility scenes
- Image and video inference support
- Trained on a Roboflow foggy dataset
- Clean project structure following ML best practices
- Deployment-ready inference pipeline

---

## 🧠 Project Workflow

1. Dataset preparation and annotation (YOLO format)
2. Model training using YOLO
3. Evaluation on validation images
4. Inference on images and videos
5. Deployment-ready application logic

---

## 📂 Project Structure

<pre>
yolo-foggy-object-detection/
├── app.py
├── data.yaml
├── requirements.txt
├── README.md
├── .gitignore
├── templates/
├── static/
└── notebooks/
</pre>

---

## 📊 Dataset Information

This project uses the **Foggy Dataset** provided via Roboflow.

- Dataset size: 4043 images  
- Annotation format: YOLO  
- Object class: Person  
- License: CC BY 4.0  

🔗 Dataset source:  
https://universe.roboflow.com/hihlo/foggy-stumc

---

## ⚠️ Model & Dataset Files

Due to GitHub size limitations, the following are **not included** in this repository:

- ❌ Trained model weights (`.pt` files)
- ❌ Dataset images and labels
- ❌ Training outputs (`runs/`, logs)

You can:
- Download pretrained YOLO weights from Ultralytics
- Train the model using the provided configuration and dataset

This keeps the repository clean and lightweight.

---

## 🛠️ Tech Stack

- Python
- YOLO
- OpenCV
- NumPy
- Flask
- Roboflow Dataset

# 🚗 Automatic License Plate Detection System using YOLOv8 & Streamlit

## 📌 Project Overview

This project is an end-to-end Automatic License Plate Detection System built using **YOLOv8**, **OpenCV**, and **Streamlit**. The application allows users to upload images or videos and automatically detects vehicle license plates with confidence scores.

The model was trained on a custom license plate dataset and deployed through an interactive Streamlit web application for real-time inference.

---

## 🚀 Features

* License Plate Detection using YOLOv8
* Image Upload Support
* Video Upload Support
* Bounding Box Visualization
* Confidence Score Display
* Interactive Streamlit Web Application
* End-to-End Deployment Pipeline

---

## 🛠️ Tech Stack

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* Streamlit
* NumPy
* Pandas
* Matplotlib

---

## 📂 Project Structure

```text
license_plate_project/
│
├── best.pt
├── yolo_applicaiton.py
├── requirements.txt
├── temp/
├── output/
└── README.md
```

---

## 📊 Model Training Workflow

1. Load XML annotations dataset
2. Convert annotations into YOLO format
3. Split dataset into Train / Validation / Test sets
4. Train YOLOv8 model
5. Evaluate model performance
6. Save trained weights (`best.pt`)
7. Deploy using Streamlit

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/Kashish-x1/license-plate-detection-yolov8.git
cd license-plate-detection-yolov8
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Mac/Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Application

```bash
streamlit run yolo_applicaiton.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

---

## 📸 Sample Output

The system detects vehicle license plates and highlights them with bounding boxes along with confidence scores.

---

## 🎯 Future Improvements

* OCR Integration for Plate Number Recognition
* Real-Time Webcam Detection
* Vehicle Tracking Support
* Cloud Deployment (AWS / Render / Streamlit Cloud)

---

## 👨‍💻 Author

**Kashish**

Data Analyst | Machine Learning Enthusiast | Computer Vision Projects

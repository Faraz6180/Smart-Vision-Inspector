# 👁️ Smart Vision Inspector

An AI-powered Computer Vision application built with Hugging Face Transformers and Streamlit that performs real-time object detection, image analysis, and visual inspection using state-of-the-art deep learning models.

---

## 🚀 Features

* Upload images directly from your device
* AI-powered object detection
* Automatic bounding box visualization
* Object counting and analysis
* Detection confidence scoring
* Interactive Streamlit web interface
* Deployable on Hugging Face Spaces

---
## 🚀Demo and Live Link
Link:
https://huggingface.co/spaces/Faraz618/Smart-Vision-Inspector
<img width="1357" height="602" alt="image" src="https://github.com/user-attachments/assets/7fef462a-7571-4d93-b7c8-c2c66a276abc" />




## 🏗️ Project Architecture

```text
Input Image
     │
     ▼
Image Processing
     │
     ▼
YOLOS Tiny Model
(Hugging Face)
     │
     ▼
Object Detection
     │
     ▼
Bounding Boxes
     │
     ▼
Object Summary Report
```

---

## 📂 Project Structure

```text
smart-vision-inspector/

├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🛠️ Technology Stack

| Component        | Technology                |
| ---------------- | ------------------------- |
| Frontend         | Streamlit                 |
| Computer Vision  | Hugging Face Transformers |
| Detection Model  | YOLOS Tiny                |
| Image Processing | Pillow                    |
| Deep Learning    | PyTorch                   |
| Deployment       | Hugging Face Spaces       |
| Language         | Python                    |

---

## 🧠 How It Works

### Step 1: Image Upload

Users upload an image through the Streamlit interface.

### Step 2: Object Detection

The image is processed using the YOLOS Tiny object detection model from Hugging Face.

### Step 3: Bounding Box Generation

Detected objects are highlighted with bounding boxes and labels.

### Step 4: Result Analysis

The application generates:

* Object labels
* Confidence scores
* Object counts
* Detection summary

---

## 📊 Skills Demonstrated

This project demonstrates practical Computer Vision and AI Engineering skills including:

### Computer Vision

* Object Detection
* Image Recognition
* Visual Analysis

### Deep Learning

* Transformer-based Vision Models
* Inference Pipelines
* Model Deployment

### AI Engineering

* Hugging Face Integration
* Streamlit Development
* Production Deployment
* Resource Optimization

### Software Engineering

* Python Development
* Interactive UI Design
* Cloud Deployment

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/smart-vision-inspector.git

cd smart-vision-inspector
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run locally:

```bash
streamlit run app.py
```

---

## 🌐 Deployment on Hugging Face Spaces

### Create a Space

Select:

```text
SDK: Streamlit
Hardware: CPU Basic
```

### Upload Files

```text
app.py
requirements.txt
README.md
.gitignore
```

### Deploy

Push the repository and wait for the build to complete.

---

## 📸 Example Output

### Input

An uploaded image containing people, vehicles, or common objects.

### Detection Output

```text
person: 3
car: 2
dog: 1
```

### Visual Result

* Bounding boxes drawn around detected objects
* Confidence scores displayed
* Summary report generated

---

## 🎯 Use Cases

* Smart Surveillance
* Retail Analytics
* Inventory Monitoring
* Traffic Analysis
* AI-Powered Image Inspection
* Computer Vision Learning Projects

---

## 🔮 Future Improvements

* Image Captioning
* OCR Integration
* Face Detection
* Instance Segmentation
* Real-Time Webcam Detection
* Video Object Detection
* Report Export Functionality
* Multi-Model Support

---

## 📄 License

MIT License

---

## 👨‍💻 Author

Built as a Computer Vision portfolio project demonstrating object detection, deep learning, Hugging Face Transformers, and AI deployment workflows.

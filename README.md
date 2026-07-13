# Remote-Sensing-Image-Summarization-Using-Object-Annotation-and-LLMs

An AI-powered geospatial image understanding pipeline that detects objects from satellite imagery, extracts geographic information, and generates natural language summaries using Large Language Models (LLMs).

## 📖 Overview

This project presents an AI-powered geospatial image understanding pipeline that automatically analyzes satellite imagery using deep learning and Large Language Models (LLMs).

The system detects multiple land-cover objects such as buildings, roads, vehicles, ships, bridges, airports, and other infrastructure from remote sensing images. It then converts the detected objects into structured annotations with geographic information and generates human-readable summaries using an LLM.

The objective is to bridge the gap between computer vision and natural language understanding, enabling automated interpretation of satellite imagery for real-world applications.

---

## 🚀 Features

- Satellite image preprocessing
- Object Detection using YOLO
- Multi-object annotation generation
- Bounding box visualization
- Geographic coordinate extraction
- Scene understanding
- Automatic image summarization using Google Gemini LLM
- Modular AI pipeline
- Notebook implementation for experimentation

---

## 🏗️ Project Pipeline

```text
Satellite Image
       │
       ▼
Image Preprocessing
       │
       ▼
Object Detection (YOLO)
       │
       ▼
Bounding Boxes & Labels
       │
       ▼
Object Annotation
       │
       ▼
Geospatial Information Extraction
       │
       ▼
Prompt Engineering
       │
       ▼
Google Gemini LLM
       │
       ▼
Natural Language Summary
```

---

## 🛠️ Technologies Used

- Python
- YOLOv11
- OpenCV
- NumPy
- Matplotlib
- Pillow
- Google Gemini API
- Jupyter Notebook

---

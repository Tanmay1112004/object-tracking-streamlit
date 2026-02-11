# 🚗 Object Tracking Streamlit App

A **high-performance web application** for real-time **object detection and tracking in videos**, built using **OpenCV and Streamlit**.

Designed with a focus on **speed, clarity, and practical usability**, this app provides an efficient computer vision pipeline with customizable controls and clean output.

---

## 🖼 Demo Preview

<p align="center">
  <img src="https://github.com/Tanmay1112004/object-tracking-streamlit/blob/main/screenshots/Screenshot%202025-09-06%20130009.png" width="45%">
  <img src="https://github.com/Tanmay1112004/object-tracking-streamlit/blob/main/screenshots/Screenshot%202025-09-06%20130235.png" width="45%">
</p>

<p align="center">
  <img src="https://github.com/Tanmay1112004/object-tracking-streamlit/blob/main/screenshots/Screenshot%202025-09-06%20130304.png" width="45%">
  <img src="https://github.com/Tanmay1112004/object-tracking-streamlit/blob/main/screenshots/Screenshot%202025-09-06%20130331.png" width="45%">
</p>

---

## 📌 Overview

This application enables users to:

* Upload a video file
* Adjust tracking and performance parameters
* Process object tracking efficiently
* Download the final annotated output video

It eliminates unnecessary UI overhead and focuses purely on **efficient video processing and clean results**.

Ideal for:

* Computer Vision demonstrations
* Academic and final-year projects
* Rapid prototyping of tracking pipelines
* Performance benchmarking experiments

---

## ✨ Key Features

### 🎥 Video Upload

* Supports `.mp4`, `.avi`, and `.mov` formats
* Easy drag-and-drop interface

### 🎛 Adjustable Tracking Controls

* Frame skipping for performance optimization
* Resize width for memory and speed control
* Minimum object area filtering to remove noise

### 📊 Processing Insights

* Real-time progress bar
* Total frames processed
* Number of objects detected
* Processing time statistics

### 📥 Export Capability

* Download the final processed tracking video instantly

### 🧼 Clean & Minimal UI

* No unnecessary visual clutter
* Designed for speed and usability

---

## 🛠 Tech Stack

| Component       | Technology                |
| --------------- | ------------------------- |
| Language        | Python 3.8+               |
| Framework       | Streamlit                 |
| Computer Vision | OpenCV                    |
| Deployment      | Local / GitHub Codespaces |

---

## ⚡ Run Locally

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Start the Application

```bash
streamlit run app.py
```

### 3️⃣ Open in Browser

```
http://localhost:8501
```

---

## 🐳 Run in GitHub Codespaces

### Install System Dependencies

```bash
sudo apt-get update && sudo apt-get install -y libgl1
```

### Install Python Requirements

```bash
pip install -r requirements.txt
```

### Run the App

```bash
streamlit run app.py --server.port 8000 --server.address 0.0.0.0
```

Open the forwarded port in your browser.

---

## 🚀 Performance Optimization Strategy

This version is intentionally optimized for speed:

* ❌ No live frame rendering during processing
* ✅ Final processed video output only
* ⚙ Frame skipping and resizing controls
* 📊 Lightweight metric reporting

Result: **Reduced lag, faster execution, cleaner results.**

---

## 🎯 Ideal Use Cases

* Object tracking demonstrations
* Academic and research experiments
* CV pipeline prototyping
* Performance comparison studies

---

## 🏗 Project Architecture

```
object-tracking-streamlit/
│
├── app.py
├── requirements.txt
├── screenshots/
└── README.md
```

---

## ⭐ Why This Project Stands Out

* Clean architecture
* Performance-first design
* Practical computer vision implementation
* Ready for demos, portfolio, and academic submission

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
📩 [tanmaykshirsagar001@gmail.com](mailto:tanmaykshirsagar001@gmail.com)

If this project adds value, consider giving it a ⭐ on GitHub.

---

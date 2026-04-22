# 🚗 Real-Time Object Tracking Web App

### High-Performance Video Processing with OpenCV + Streamlit

> A production-style computer vision application for efficient object detection and tracking in uploaded videos — optimized for speed, clarity, and usability.

---

## 📌 Project Overview

This application enables real-time object tracking through an optimized video processing pipeline built using:

* 🎥 **OpenCV** – Computer vision engine
* 🌐 **Streamlit** – Interactive web interface
* ⚡ Performance-first frame processing strategy

Users can upload videos, tune performance parameters, and download annotated tracking outputs — all through a clean and minimal UI.

This project demonstrates practical CV engineering, not just model experimentation.

---


---

## 🚀 Core Capabilities

### 🎥 Smart Video Upload

* Supports `.mp4`, `.avi`, `.mov`
* Drag-and-drop interface
* Local processing (no cloud dependency)

---

### 🎛 Performance Control Panel

Users can dynamically adjust:

* **Frame Skipping** → Faster processing
* **Resize Width** → Memory & speed optimization
* **Minimum Object Area** → Noise filtering

This allows trade-off control between speed and precision.

---

### 📊 Processing Analytics

During execution:

* Progress tracking bar
* Total frames processed
* Objects detected count
* Total execution time

Designed for benchmarking and experimentation.

---

### 📥 Exportable Results

* Annotated video with bounding boxes
* Instant download after processing
* Clean overlay rendering

---

## ⚙️ Performance Optimization Strategy

Unlike naive implementations, this app is built for efficiency:

```
Video Input
    ↓
Frame Sampling (Skip Strategy)
    ↓
Resize Optimization
    ↓
Contour / Object Detection
    ↓
Bounding Box Annotation
    ↓
Video Writer Output
```

Key decisions:

✔ No live frame rendering during processing
✔ Lightweight metric reporting
✔ Controlled memory footprint
✔ Faster execution on mid-range hardware

---

## 🛠 Tech Stack

| Layer       | Technology         |
| ----------- | ------------------ |
| Programming | Python 3.8+        |
| CV Engine   | OpenCV             |
| UI          | Streamlit          |
| Deployment  | Local / Codespaces |

---

## 🚀 Run Locally

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Launch App

```bash
streamlit run app.py
```

### 3️⃣ Open in Browser

```
http://localhost:8501
```

---

## 🐳 Run in GitHub Codespaces

### Install System Dependency

```bash
sudo apt-get update && sudo apt-get install -y libgl1
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Run Server

```bash
streamlit run app.py --server.port 8000 --server.address 0.0.0.0
```

Open forwarded port in browser.

---

## 🎯 Ideal Use Cases

* 🎓 Academic CV projects
* 🧪 Vision pipeline benchmarking
* 🏭 Industrial tracking prototypes
* 🚦 Traffic monitoring experiments
* 📦 Warehouse object monitoring

---

## 🏗 Project Structure

```
object-tracking-streamlit/
│
├── app.py
├── requirements.txt
├── screenshots/
└── README.md
```

---

## 📈 Why This Project Stands Out

This demonstrates:

✔ Practical computer vision engineering
✔ Performance optimization awareness
✔ Real-world deployment thinking
✔ Clean UI + backend integration
✔ Efficient video processing pipeline design

This is not just “draw bounding boxes.”
This shows you understand **pipeline efficiency and system constraints**.

---

## 🔮 Future Enhancements

* YOLO-based object detection integration
* Deep SORT multi-object tracking
* Real-time webcam mode
* GPU acceleration (CUDA OpenCV)
* REST API version (FastAPI backend)
* Docker containerization

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
📩 [tanmaykshirsagar001@gmail.com](mailto:tanmaykshirsagar001@gmail.com)
🔗 GitHub: [https://github.com/Tanmay1112004](https://github.com/Tanmay1112004)

---

## ⭐ Support

If this project helped or inspired you, consider giving it a ⭐ on GitHub.

It genuinely helps visibility.

---

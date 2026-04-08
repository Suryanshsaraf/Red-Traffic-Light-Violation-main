# Red Traffic Light Violation Detection System

This project is a high-performance **Red Traffic Light Violation Detection System** that leverages state-of-the-art computer vision to automate traffic enforcement.

### 🚦 Project Overview
This system monitors traffic feeds to detect and record vehicles that bypass red lights. It combines **YOLOv10** for robust object detection with custom **HSV-based color filtering** for precise traffic light state analysis.

---

### ✨ Key Features
*   **Real-time Vehicle Detection**: Uses YOLOv10s for high-speed, accurate detection of cars, trucks, and buses.
*   **Traffic Light State Analysis**: Intelligent color thresholding to distinguish between Red and Green signals in varying lighting conditions.
*   **Dynamic Tracking**: Implements a custom Euclidean distance-based tracker to maintain unique IDs for vehicles across frames.
*   **Violation Evidence Capture**: Automatically saves high-resolution images of violating vehicles into date-stamped folders for evidentiary use.
*   **Region of Interest (ROI) Mapping**: Customizable detection zones to focus specifically on stop lines and intersection boundaries.

### 🛠️ Tech Stack
*   **Language**: Python 3.13+
*   **AI Model**: YOLOv10 (Ultralytics)
*   **Computer Vision**: OpenCV, CVZone
*   **Data Handling**: Pandas, NumPy

### 🚀 Quick Start
1.  **Clone the Repo**:
    ```bash
    git clone https://github.com/Suryanshsaraf/Red-Traffic-Light-Violation-main.git
    cd Red-Traffic-Light-Violation-main
    ```
2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the System**:
    ```bash
    python pmain1.py
    ```

### 📁 Directory Structure
*   `pmain1.py`: The main execution engine.
*   `test1.py`: Traffic light color detection logic.
*   `tracker.py`: Object tracking implementation.
*   `saved_images/`: Automated storage for violation logs.
*   `yolov10s.pt`: Pre-trained weights for vehicle detection.
*   `tr.mp4`: Test video file.
*   `coco.txt`: Class names for detection.

---

**Potential GitHub Tagline:**
> 🚗🚦 AI-powered traffic enforcement system using YOLOv10 and OpenCV to detect and log red-light violations in real-time.

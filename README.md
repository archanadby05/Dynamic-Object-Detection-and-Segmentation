## Background Subtraction Methods in OpenCV

This repository demonstrates multiple background subtraction techniques using **OpenCV**, commonly used for motion detection, object tracking, and video analysis.

### 🌟 Implemented Methods:
1. **MOG (Mixture of Gaussians)** – A classic background subtraction algorithm.
2. **MOG2 (Improved Mixture of Gaussians)** – An adaptive version of MOG that detects shadows.
3. **KNN (K-Nearest Neighbors)** – Uses a distance-based approach to separate the foreground from the background.
4. **Frame Differencing** – Compares consecutive frames to detect motion.
5. **Running Average Background Subtraction** – Maintains an averaged background model.

---

### 🚀 Open in Google Colab  
Click below to open and run the notebook directly in Google Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/YOUR_NOTEBOOK.ipynb)

---

### 📂 Files in This Repository:
- `background_subtraction.ipynb` → Jupyter Notebook containing all five background subtraction methods.
- `sample.mp4` → Sample video file (You need to provide your own video for testing).
- `README.md` → This documentation file.

---

### 📦 Installation and Requirements
Make sure you have **Python** and the necessary libraries installed. If not, install them using:

```bash
pip install opencv-python numpy

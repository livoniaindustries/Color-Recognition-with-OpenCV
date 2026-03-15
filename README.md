# 🎨 Real-Time Color Recognition with OpenCV

This project uses **Python** and **OpenCV** to detect the color of the pixel located at the **center of the webcam frame** in real time.

The program captures video from your webcam, converts the frame to **HSV color space**, reads the pixel at the center, and classifies the color based on its **Hue value**.

---

## 📸 Features

- Real-time webcam video capture
- HSV color space conversion
- Center pixel color detection
- Color classification:
  - Red
  - Orange
  - Yellow
  - Green
  - Blue
  - Violet
- Displays the detected color on the screen

---

## 🛠 Requirements

- Python 3.x
- OpenCV
- NumPy

---

## ⚙️ Installation

Create a virtual environment:

```bash
python -m venv venv
```

Activate the environment:

### Windows
```bash
venv\Scripts\activate
```

### macOS / Linux
```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install opencv-python
pip install numpy
```

---

## ▶️ Run the Program

```bash
python color_recognition.py
```

Press **ESC** to exit the application.

---

## 🧠 How It Works

1. The webcam captures frames continuously.
2. Each frame is converted from **BGR → HSV**.
3. The program reads the **HSV value of the center pixel**.
4. The **Hue value** determines the color category.
5. The detected color is displayed on the screen.

---

## 🖥 Example

The program shows:
- A **center marker**
- A **color label**
- The **live webcam feed**

Point different colored objects at the center of the screen to see the detected color.

---

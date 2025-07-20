# 🏗️ 2D to 3D Blueprint Converter Web App

This is an AI-powered web application that converts 2D floor plan blueprints into interactive 3D models. It uses **Flask**, **OpenCV**, **AI object detection**, and **Three.js** for a seamless experience from upload to visualization.

---

## 🚀 Features

- 🧠 AI-powered 2D blueprint processing
- 🧱 Wall, door, and window detection using OpenCV + YOLO
- 🏠 Automatic 3D model generation (OBJ/MTL and glTF support)
- 🌐 Simple and modern web interface (drag & drop + progress bar)
- 🎮 Interactive 3D rendering using Three.js

---

## 📁 Project Structure

project-root/
│
├── static/ # JavaScript, CSS, and assets
├── templates/ # HTML templates (index.html, result.html)
├── uploads/ # Uploaded floor plan images
├── models/ # Trained AI models (YOLOv8, etc.)
├── app.py # Flask backend
├── converter.py # Image processing and 3D model generation
├── requirements.txt # Python dependencies
└── README.md # This file

yaml
Copy
Edit

---

## 🛠️ Installation

Make sure Python 3.8+ is installed.

```bash
# Clone the repository
git clone https://github.com/yourusername/blueprint-to-3d-model.git
cd blueprint-to-3d-model

# Create virtual environment
python -m venv venv
source venv/bin/activate         # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

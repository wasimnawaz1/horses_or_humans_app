# 🐎👤 Horses or Humans Image Classifier

[![Python](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)  
[![Flask](https://img.shields.io/badge/Flask-2.x-lightgrey.svg)](https://flask.palletsprojects.com/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  

This project is a **web-based application** that uses a deep learning model to classify images as either **"horse"** or **"human."**  
It provides a simple interface where users can upload an image and instantly receive a classification result.

---

## 📖 Project Description

The core of this application is a **Convolutional Neural Network (CNN)** built with **TensorFlow** and **Keras**.  
The model is trained on a dataset of horse and human images to achieve high accuracy in distinguishing between the two.  

The web app is built with **Flask (or Django)** and serves a frontend that allows users to interact with the model by uploading images.

---

## ✨ Features

- **Image Classification**: Accurately classifies uploaded images as horse or human.  
- **User-Friendly Interface**: Clean and simple web interface for uploads and results.  
- **Deep Learning Model**: Uses a pre-trained/custom-built CNN for image analysis.  
- **Simple Deployment**: Easily run the project locally.  

---

## ⚙️ Prerequisites

To run this project, ensure you have:

- Python **3.7+**  
- `pip` (Python package installer)  

---

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/wasimnawaz1/horses_or_humans_app.git
cd horses_or_humans_app
````

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### 1. Run the Application

```bash
python app.py  # or your main server file
```

### 2. Access the App

Open your browser and go to:

```
http://127.0.0.1:5000
```

### 3. Upload an Image

Click **"Upload Image"** and select an image containing either a horse or a human.
The app will process the image and display the classification result.

---

## 📸 Demo

Here’s an example of how the app looks in action:

### Web Interface Screenshot

![App Screenshot](docs/screenshot.png)

### Demo GIF (Image Upload & Classification)

![Demo GIF](docs/demo.gif)

> *(Replace `docs/screenshot.png` and `docs/demo.gif` with actual file paths once you add them to your repo.)*

---

## 📂 File Structure

```
horses_or_humans_app/
├── app.py                  # Main application file (Flask server)
├── model/                  # Directory to store the trained model
│   └── horses_or_humans.h5 # The trained Keras/TensorFlow model file
├── static/                 # Static assets (CSS, JS)
├── templates/              # HTML templates for the web interface
│   └── index.html
├── requirements.txt        # Python dependencies
├── docs/                   # Screenshots / GIFs for README
│   ├── screenshot.png
│   └── demo.gif
└── README.md
```

---

## 📦 Dependencies

* **TensorFlow** – Core deep learning library
* **Keras** – High-level neural networks API
* **Flask** – Web server framework
* **NumPy** – Numerical operations
* **Pillow (PIL)** – Image processing

---

## 🤝 Contributing

Contributions are welcome!
If you have ideas for improvements, new features, or bug fixes, please open an **issue** or submit a **pull request**.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

```

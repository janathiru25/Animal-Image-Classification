# 🐾 Animal Image Classification using EfficientNet-B0

A deep learning-based web application that classifies animal images into one of 10 categories using the EfficientNet-B0 architecture. The application is built with **PyTorch** and deployed using **Streamlit**, providing an interactive interface for image classification.

---

## 📌 Features

- 🧠 EfficientNet-B0 Transfer Learning
- 📷 Upload JPG, JPEG, and PNG images
- 📊 Top-3 prediction probabilities
- 📈 Interactive confidence chart using Plotly
- 📖 Animal information display
- 📥 Download prediction report
- 🌐 Streamlit web interface
- ⚡ Fast CPU inference

---

## 🗂️ Dataset

This project uses the **Animals10 Dataset** from Kaggle.

### Classes

- Butterfly
- Cat
- Chicken
- Cow
- Dog
- Elephant
- Horse
- Sheep
- Spider
- Squirrel

**Dataset Size:** 28,000+ images

---

## 🧠 Model

- EfficientNet-B0
- Pretrained on ImageNet
- Transfer Learning
- Fine-tuned for 10 animal classes

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- Streamlit
- Plotly
- Pandas
- Pillow

---

## 📂 Project Structure

```text
Animal-Classification-EfficientNet/

│
├── app.py
├── train.py
├── requirements.txt
├── README.md
│
├── assets/
│
├── dataset/
│
├── models/
│     └── best_model.pth
│
├── outputs/
│
├── notebooks/
│
└── src/
      ├── model.py
      ├── predict.py
      └── utils.py
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Animal-Classification-EfficientNet.git

cd Animal-Classification-EfficientNet
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser:

```
http://localhost:8501
```

---

## 📸 Application Preview

Add screenshots of the application here after deployment.

Example:

```
assets/app_preview.png
```

---

## 📈 Future Improvements

- Mobile responsive UI
- Dark and Light theme
- Model comparison (ResNet, DenseNet, EfficientNet)
- Multi-language support
- Cloud deployment

---

## 👨‍💻 Author

**Jananapriya**

Computer Science Student

Interested in:

- Machine Learning
- Deep Learning
- Computer Vision
- Artificial Intelligence

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

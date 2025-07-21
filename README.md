# 🧠 X-ray Image Classification with Deep Learning

This repository contains a full pipeline for classifying chest X-ray images into **COVID-19**, **Pneumonia**, or **Normal** using deep learning and image processing. The solution combines a ResNet-based CNN for feature extraction with PCA for dimensionality reduction and KNN (Bray-Curtis distance) for final classification.

---

## 🚀 Features

- ✅ Preprocessing with `imadjust` filter to enhance image quality.
- ✅ Feature extraction using **ResNet** (pre-trained).
- ✅ Dimensionality reduction using **PCA** with 100 components.
- ✅ Classification using **KNN** with Bray-Curtis distance.
- ✅ Visualization of PCA variance, confusion matrix, and classification reports.

---

## 📁 Project Structure

```
📂 Xray-Classifier/
├── notebook.ipynb         # Main notebook with all code
├── README.md              # Project overview and usage instructions
```

---

## 🧰 Tech Stack

- Python 3.8+
- PyTorch
- OpenCV
- NumPy & Pandas
- scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🛠️ Installation

1. **Clone this repo**
```bash
git clone https://github.com/Kunj-Pate1/PulmoScans--AI-Seminar-Workshp

```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook notebook.ipynb
```

---

## 📊 Sample Output

- Enhanced X-ray images (after preprocessing)
- PCA variance ratio plots
- Confusion matrix heatmaps
- Classification reports

---

## ⚠️ Disclaimer

> This project is built for educational and experimental purposes. It should **not** be used for clinical or diagnostic purposes without extensive validation and medical review.

---

## 👤 Author

Developed by Ishan and Kunj

---

## 📄 License

MIT License. See `LICENSE` file for details.

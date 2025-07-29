# 🧠 deepfake-detection-efficientnet

Detecting deepfake images using **EfficientNetB4 CNN** with transfer learning and face-level binary classification.

---

## 📌 Project Highlights

-  Based on **EfficientNetB4**
-  Binary classification: `Real` vs `Fake`
-  Uses **transfer learning** from ImageNet
-  Preprocessing includes resizing, normalization, and face cropping (if applied)
-  Trained using TensorFlow/Keras

---

## 📁 Dataset Structure

This model expects a folder structure like:

dataset/
├── real/
│ ├── real1.jpg
│ ├── real2.jpg
│ └── ...
└── fake/
├── fake1.jpg
├── fake2.jpg
└── ...


> 📝 Datasets can be sourced from [Kaggle](https://www.kaggle.com/competitions/deepfake-detection-challenge) or [FaceForensics++](https://github.com/ondyari/FaceForensics).

---

## 🛠️ Requirements

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt



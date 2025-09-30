# Age Prediction with Deep Learning

This project uses computer vision and deep learning to predict a person’s age from facial images.  
The model is built on a **ResNet50 backbone** and trained on the **ChaLearn Looking at People** dataset.

---

## 📌 Overview
- Developed a **ResNet50-based convolutional neural network** to perform age regression.  
- Applied **data preprocessing & augmentation** with `ImageDataGenerator` for robust training.  
- Optimized training on GPU to accelerate convergence and reduce error.  

---

## 🛠️ Tech Stack
- Python (NumPy, Pandas, Matplotlib)
- TensorFlow / Keras
- ResNet50 (transfer learning)
- ImageDataGenerator (augmentation & preprocessing)

---

## 📊 Results
- Achieved a **Mean Absolute Error (MAE) of 7.8 years** (beating the project target ≤ 8).  
- Demonstrated the effectiveness of **transfer learning** for computer vision tasks.  

---

## 📂 Repository Structure

```

age-prediction-deep-learning/
│
├── notebooks/
│ └── age_prediction.ipynb # Jupyter notebook with full pipeline
├── data/ # (empty) place dataset here locally
├── results/ # model outputs, charts
├── requirements.txt # dependencies
└── README.md

```

---

## ⚙️ Setup & Usage

1. Clone the repository:
   ```
   git clone https://github.com/ekayasare/age-prediction-deep-learning.git
   cd age-prediction-deep-learning

pip install -r requirements.txt

Download the ChaLearn LAP dataset
 and place the images + labels into the data/ folder.

Run the notebook:

jupyter notebook notebooks/age_prediction.ipynb


Author

Ekay (Emmanuel Nyarko Asare)
AI/ML Data Scientist | Deep Learning Enthusiast
LinkedIn
 | GitHub


---

### ✅ requirements.txt (from your notebook)
```txt
tensorflow>=2.15
keras>=2.15
scikit-learn>=1.5
pandas>=2.2
numpy>=1.26
matplotlib>=3.9

# 🩺 AI Skin Disease Detector

An AI-powered web application built with **TensorFlow** and **Streamlit** that detects common skin diseases from uploaded images.  
The app provides predictions, confidence scores, and practical **skin health precautions**.  
⚠️ This project is for **educational/demo purposes only** and should not be used as a medical diagnosis.

---

## 🚀 Features
- Upload skin images (JPG/PNG).
- Predicts conditions such as:
  - Eczema
  - Melanoma
  - Atopic Dermatitis
  - Basal Cell Carcinoma
  - Melanocytic
  - Begin Kertaosis-like Lesions
  - Psoriasis pictures Lichen Planus and related diseases
  - Seborrheic Kertaosis and other benign Tumors
  - Tinea Ringworm Candidiasis and other Fungal infections
  - Warts Molluscum and other Viral Infections
  
- Displays confidence percentage.
- Provides **precautions** and **doctor consultation advice**.
- Clean, professional UI with Streamlit.

---

## 🛠️ Tech Stack
- **Python 3.10+**
- **TensorFlow / Keras** (EfficientNetB0 transfer learning)
- **Streamlit** (frontend UI)
- **PIL** (image preprocessing)
- **NumPy** (array operations)

---

## 📂 Project Structure
skin-disease-detector/
│
├── app.py                  # Streamlit frontend (UI + predictions + advice)
├── skin_disease_model.h5   # Trained TensorFlow/Keras model
├── requirements.txt        # Python dependencies
├── README.md               # Documentation
│
├── data/                   # Dataset folder (optional, if storing locally)
│   ├── train/              # Training images (organized by class)
│   ├── val/                # Validation images
│   └── test/               # Test images
│
├── notebooks/              # Jupyter notebooks for experiments
│   ├── data_cleaning.ipynb
│   ├── model_training.ipynb
│   └── evaluation.ipynb
│
├── utils/                  # Helper functions
│   ├── preprocessing.py    # Image preprocessing utilities
│   ├── visualization.py    # Plotting training curves
│   └── maps_integration.py # (Optional) Google Maps API integration
│




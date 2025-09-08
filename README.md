# Cancer Detection & Subtype Classification

This repository contains work on two projects focusing on cancer detection and subtype classification using machine learning models. The workflow includes **data cleaning**, **model training**, and **evaluation**.  

---

## 📂 Project Structure

├── data/
│ ├── p1-dataset/ # Data for Project 1 (Cancer Detection)
│ ├── p2-cleaned-data/ # Data for Project 2 (Subtype Classification)
│ ├── p2-raw-data/ # Raw data of Project 2
|
├── notebooks/
│ ├── p1-brca-detection.ipynb # Cancer Detection project notebook 
│ ├── p2-Data-Cleaning.ipynb # Data preprocessing and cleaning of dataset 2 (dataset 1 is already cleaned)
│ ├── p2-subtype-detection.ipynb # Subtype Classification project notebook
│
└── README.md


---

## 🧪 Project 1: Cancer Detection

- **Goal**: Detect whether a patient has breast cancer (binary classification).  
- **Dataset**: `data/p1-dataset/`  
- **Model Performance**:  
  - ✅ Validation Accuracy: **99%**  
  - ✅ Test Accuracy: **98%**  

This project achieved **high performance**, showing that the features used were strongly predictive for the cancer detection task.  

---

## 🧪 Project 2: Subtype Classification

- **Goal**: Identify the specific **subtype of cancer** (multi-class classification).  
- **Dataset**: `data/p2-cleande-data/`  
- **Model Performance**:  
  - ✅ Validation Accuracy: **85%**  
  - ✅ Test Accuracy: **87%**  

This project was more challenging due to multiple cancer subtypes, but the results still indicate strong classification ability.  

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/cancer-detection-projects.git


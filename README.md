# HematoVision

HematoVision is a deep learning web application for blood cell image classification. It utilizes a pre-trained CNN model built with TensorFlow and provides an interactive interface using Flask.

## 🔬 About

This project classifies microscopic images of blood cells into four categories:
- **Eosinophil**
- **Lymphocyte**
- **Monocyte**
- **Neutrophil**

The goal is to assist in the automated analysis of blood samples for medical diagnosis.

---

## 📁 Project Structure

```
HematoVision/
│
├── app.py                    # Flask backend application
├── Blood Cell.h5             # Trained model file (excluded from GitHub)
├── BloodCellClassifier.ipynb # Jupyter notebook for training/testing
├── static/                   # Folder to store uploaded images
├── templates/                # HTML templates
│   ├── home.html             # Upload interface
│   └── result.html           # Prediction result display
└── README.md                 # Project description
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/HematoVision.git
cd HematoVision
```

### 2. Install Dependencies

Make sure you have Python and pip installed. Then run:

```bash
pip install -r requirements.txt
```

Or manually install required libraries:

```bash
pip install flask tensorflow opencv-python
```

### 3. Run the App

```bash
python app.py
```

Open your browser and go to:  
👉 **http://127.0.0.1:5000/**

---

## 📓 Jupyter Notebook

- `BloodCellClassifier.ipynb` contains the code for:
  - Data preprocessing
  - CNN model building
  - Training and evaluation
  - Saving the trained model as `Blood Cell.h5`

---

## ⚠️ Notes

- The file `Blood Cell.h5` is large and not tracked on GitHub. Train your own or contact the project owner.
- Use a `.gitignore` file to avoid uploading unnecessary files:
  ```
  *.h5
  *.zip
  __pycache__/
  .ipynb_checkpoints/
  ```

---

## 🧠 Future Improvements

- Upload and predict multiple images
- Enhance UI with modern styling (Bootstrap/Tailwind)
- Deploy the app on cloud (Render, Vercel, etc.)

---

## 👩‍⚕️ Educational Purpose

This project was created during an internship to apply machine learning to healthcare data and demonstrate a practical deep learning use case using Flask and TensorFlow.

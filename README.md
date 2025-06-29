# HematoVision

A deep learning web app for blood cell image classification using Flask and TensorFlow.  
This project uses a Convolutional Neural Network (CNN) trained to classify four types of blood cells:
- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

The application allows users to upload blood cell images and returns the predicted cell type.

---

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- Flask
- OpenCV
- HTML/CSS (Milligram CSS framework)

---

## 📁 Project Structure

```
HematoVision/
│
├── app.py               # Flask application
├── Blood Cell.h5        # Trained CNN model
├── static/              # Folder to store uploaded images
│   └── (uploaded files)
├── templates/
│   ├── home.html        # Upload interface
│   └── result.html      # Result page with prediction
└── README.md            # Project documentation
```

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/VeluriRashmitha/HematoVision.git
cd HematoVision
```

### 2. Install the required packages

Make sure you have Python installed (preferably 3.8+). Then install the necessary libraries:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install flask tensorflow opencv-python
```

### 3. Run the application

```bash
python app.py
```

Then open your browser and go to:  
📍 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---
## 🧠 Model Info

The CNN model was trained using MobileNetV2 as a base model with transfer learning. It takes input images resized to 224x224 pixels and predicts the class probabilities.

---

## 📜 License

This project is open-source and free to use for educational purposes.

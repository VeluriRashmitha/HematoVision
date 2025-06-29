# HematoVision

A deep learning web app for blood cell image classification using **Flask** and **TensorFlow**.

This project uses a Convolutional Neural Network (CNN) trained to classify four types of blood cells:
- **Eosinophil**
- **Lymphocyte**
- **Monocyte**
- **Neutrophil**

The application allows users to upload blood cell images and returns the predicted cell type in a simple web interface.

---

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- Flask
- OpenCV
- HTML & CSS (Milligram CSS framework)
- Jupyter Notebook

---

## 📁 Project Structure

```
HematoVision/
│
├── app.py                    # Flask application
├── Blood Cell.h5             # Trained CNN model
├── BloodCellClassifier.ipynb # Jupyter notebook used for model development
├── .gitignore                # Git ignore rules
├── requirements.txt          # List of Python dependencies
├── static/                   # Folder to store uploaded images
│   └── (uploaded images)
├── templates/
│   ├── home.html             # Upload interface
│   └── result.html           # Result page with prediction
└── README.md                 # Project documentation
```

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/Your Username/HematoVision.git
cd HematoVision
```

### 2. Install the required packages

Make sure you have Python (preferably 3.8+) installed, then install the required libraries:

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, you can manually install:

```bash
pip install flask tensorflow opencv-python
```

### 3. Run the application

```bash
python app.py
```

Then open your browser and visit:  
📍 [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧪 Jupyter Notebook

The file [`BloodCellClassifier.ipynb`](BloodCellClassifier.ipynb) contains:

- Data preprocessing steps
- MobileNetV2-based transfer learning model
- Training and validation logic
- Model evaluation and accuracy reporting
- `Blood Cell.h5` model saving logic

You can open the notebook in Jupyter to explore how the model was built and trained.

---

## 🧠 Model Info

- **Model Architecture**: Transfer learning using MobileNetV2
- **Input Image Size**: 224x224 pixels
- **Frameworks Used**: TensorFlow, Keras
- **Model Output**: One of the four blood cell classes

---

## 📜 License

This project is open-source and free to use for learning and academic purposes.

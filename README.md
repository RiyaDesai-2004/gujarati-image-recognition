# 🔤 Gujarati Image Recognition
 
A deep learning project for recognizing Gujarati handwritten characters and digits using Convolutional Neural Networks (CNN) and Transfer Learning.
 
--- 
## 🧠 Project Overview
 
This project focuses on building an image recognition system for **Gujarati handwritten characters and digits**. It involves:
 
- Collecting and preprocessing a Gujarati digits dataset
- Training a Neural Network model to classify handwritten Gujarati digits
- Using Transfer Learning concepts (inspired by dog vs cat classification) for feature extraction
 
---
 
## 📁 Project Structure
 
```
gujarati-image-recognition/
│
├── gujarti-image-recognition-master/
│   │
│   ├── dog vs cat model/                  # Transfer learning base model
│   │   ├── notebook pdf/
│   │   │   └── dog vs cat code.pdf
│   │   ├── py notebook/
│   │   │   └── dog vs cat code.ipynb
│   │   └── tensorflow model/
│   │       ├── model link.txt
│   │       └── tensorflow feature vector model.zip
│   │
│   ├── gujarati digits dataset/           # Dataset for Gujarati digits (0–9)
│   │   ├── preprocessed images/
│   │   └── raw images/
│   │
│   ├── gujarati handwriting recognition/  # Main recognition model
│   │   ├── pdfs/
│   │   ├── python files/
│   │   │   └── model-1 nn.ipynb
│   │   └── python files for preprocessing/
│   │       ├── absolute_0-1_filtering.py
│   │       ├── augment.py
│   │       ├── get_no_of_imgs.py
│   │       └── resize_imgs.py
│   │
│   ├── .gitignore
│   └── README.md
```
 
---

 
## 🛠️ Technologies Used
 
| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| TensorFlow / Keras | Deep learning framework |
| Jupyter Notebook | Model training and experimentation |
| NumPy / Pandas | Data handling |
| OpenCV / PIL | Image preprocessing |
| Matplotlib | Visualization |
 
---
 
## ⚙️ Preprocessing Steps
 
The following scripts handle image preprocessing:
 
- **`resize_imgs.py`** — Resizes all raw images to a uniform size
- **`augment.py`** — Applies data augmentation (rotation, flipping, etc.) to increase dataset size
- **`get_no_of_imgs.py`** — Counts the number of images in each class
- **`absolute_0-1_filtering.py`** — Normalizes pixel values to the range [0, 1]
 
---
 
## 🚀 How to Run
 
### 1. Clone the repository
```bash
git clone https://github.com/RiyaDesai-2004/gujarati-image-recognition.git
cd gujarati-image-recognition
```
 
### 2. Install dependencies
```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python pillow
```
 
### 3. Preprocess the images
```bash
python "python files for preprocessing/resize_imgs.py"
python "python files for preprocessing/augment.py"
```
 
### 4. Train the model
Open and run the Jupyter Notebook:
```bash
jupyter notebook "gujarati handwriting recognition/python files/model-1 nn.ipynb"
```
 
---
 
## 📊 Dataset
 
- **Raw Images**: Original collected handwritten Gujarati digit images
- **Preprocessed Images**: Cleaned, resized, and normalized images ready for training
- Classes: Gujarati digits **0 to 9**
 
---
 
## 📌 Notes
 
- Large model files (`.pth`, `.h5`, `.zip`) are excluded via `.gitignore`
- CSV data files and virtual environment folders are also excluded
 
---
 
## 👩‍💻 Author

- GitHub: [@RiyaDesai-2004](https://github.com/RiyaDesai-2004)
 
---
 

# 📸 Image Processing & Deep Learning for Diabetic Retinopathy Detection  
🧠 Empowering early diagnosis through AI & Computer Vision  
[⭐ Star this repo](https://github.com/sanvega9/Image-Processing-Diabetes-Retinopathy) if you find it helpful!

---

## 🌟 Overview
Diabetic Retinopathy (DR) is a diabetes complication that damages the retina and can lead to blindness. This project uses **deep learning (MobileNetV2)** and **image preprocessing techniques** to detect signs of DR in retinal images — making early diagnosis more accessible and efficient.

---

## 📂 Project Structure

| File/Folder                  | Description                                        |
|-----------------------------|----------------------------------------------------|
| `archive/`                  | Contains retinal images for training/testing       |
| `cnn.txt`                   | Model summary or experiment notes                  |
| `deep_learning_DR.py`       | Main deep learning script using MobileNetV2        |
| `image_processing_DR.py`    | Preprocessing retinal images for model input       |
| `dr_detector_mobilenetv2.h5`| Pre-trained Keras model file                        |

---

## 🧪 Technologies Used
- 🔹 Python 3.x  
- 🔹 TensorFlow / Keras  
- 🔹 OpenCV  
- 🔹 NumPy  
- 🔹 Matplotlib  

---

## 🚀 How to Run

```bash
# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Step 1: Install required libraries
pip install -r requirements.txt

# Step 2: Preprocess the data
python image_processing_DR.py

# Step 3: Run the deep learning model
python deep_learning_DR.py

# 🧠👁️ Eye Disease Detection with Deep Learning  

This project uses a deep learning model to detect various eye diseases from retinal OCT images.  
The application is deployed using **Streamlit** to provide a simple and interactive user interface.  

Along with predictions, the app provides personalized medical recommendations based on the detected condition.

---

## 🚀 Live Demo  

🔗 **Try the app here:**  
https://eye-disease-detection-2.streamlit.app/

---

## ✨ Features  

- ✅ Upload an eye image and get a disease prediction  
- ✅ Supports 4 classes: **CNV, DME, DRUSEN, NORMAL**  
- ✅ Provides medical recommendations for each detected condition  
- ✅ Clean and responsive UI built with Streamlit  
- ✅ Model trained using **MobileNetV3** for accurate results  

---

## 🧠 Model Information  

- **Architecture:** MobileNetV3  
- **Framework:** TensorFlow / Keras  
- **Input Size:** `224x224`  
- **Output Classes:**  
  - `CNV`  
  - `DME`  
  - `DRUSEN`  
  - `NORMAL`  

The model was trained on labeled retinal OCT images and optimized for multi-class classification.

---

## 🩺 Disease Classes & Description  

- **CNV (Choroidal Neovascularization)**  
  Abnormal blood vessel growth under the retina.  

- **DME (Diabetic Macular Edema)**  
  Swelling in the retina caused by diabetes.  

- **DRUSEN**  
  Yellow deposits under the retina, linked to macular degeneration.  

- **NORMAL**  
  No visible signs of retinal disease.  

Each class has a tailored recommendation stored in `Recommendation.py` and displayed after prediction.

---

## 🖥️ Installation  

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/Eye-Disease-Detection.git
cd Eye-Disease-Detection
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📁 Project Structure  

```bash
Eye-Disease-Detection/
│
├── eye-disease(1).ipynb      # Model training notebook
├── app.py                   # Main Streamlit app
├── new_model.keras          # Trained MobileNetV3 model
├── Recommendation.py        # Disease-specific recommendations
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
```

---

## 📸 Demo  

Here’s a quick look at the app interface:

![App Interface 1](https://github.com/user-attachments/assets/15c3fcff-1885-4a54-99fa-6eabea69215e)

![App Interface 2](https://github.com/user-attachments/assets/c2bef1f4-dbac-4cd7-8d16-40c4f155c7c3)

---

## 📚 Dataset  

The model was trained using the **Retinal OCT Images Dataset** available on Kaggle:

🔗 https://www.kaggle.com/datasets/paultimothymooney/kermany2018  

The dataset includes labeled images for:

- CNV  
- DME  
- DRUSEN  
- NORMAL  

---

## 📥 How to Use the App  

1. **Open the Live Demo Link**  
   https://eye-disease-detection-2.streamlit.app/  

2. **Upload Image**  
   Go to the *"Disease Identification"* page from the sidebar and upload an OCT retinal image  
   (You can use images from the Kaggle dataset test folder).  

3. **Click Predict**  
   Press the **Predict** button.  

4. **View Results**  
   The model will display the predicted disease class along with a detailed medical recommendation and visual analysis.

---

## 👩‍💻 Author  

**Rokia Yasser**  
Machine Learning Engineer  

🔗 LinkedIn:  
https://www.linkedin.com/in/rokia-yasser-1a8a4922b/

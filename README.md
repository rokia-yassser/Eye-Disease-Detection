# Eye Disease Detection with Deep Learning 🧠👁️

This project uses a deep learning model to detect various eye diseases from retinal images. The application is deployed using **Streamlit** to provide a simple and interactive user interface. Along with predictions, the app provides personalized recommendations based on the detected condition.

---

## 🚀 Features

- ✅ Upload an eye image and get a disease prediction
- ✅ Supports 4 classes: CNV, DME, DRUSEN, and NORMAL
- ✅ Gives medical recommendations for each detected condition
- ✅ Clean and responsive UI using Streamlit
- ✅ Model trained with MobileNetV3 for accurate results

---

## 🧠 Model Info

- Model architecture: **MobileNetV3**
- Framework: **TensorFlow / Keras**
- Input image size: `224x224`
- Trained on a dataset of retinal images
- Model output: one of four classes: 
  - `CNV`
  - `DME`
  - `DRUSEN`
  - `NORMAL`

---

## 🩺 Disease Classes & Recommendations

- **CNV**: Choroidal neovascularization – abnormal blood vessel growth under the retina.
- **DME**: Diabetic macular edema – swelling in the retina due to diabetes.
- **DRUSEN**: Yellow deposits under the retina, linked to macular degeneration.
- **NORMAL**: No signs of disease.

Each class has a tailored recommendation stored in the `Recommendation.py` file and displayed after prediction.

---

## 🖥️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Eye-Disease-Detection.git
cd Eye-Disease-Detection

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
📁 Project Structure
bash
Copy
Edit
Eye-Disease-Detection/
│
├── app.py                  # Main Streamlit app
├── new_model.h5           # Trained MobileNetV3 model
├── Recommendation.py      # Disease-specific advice
├── requirements.txt       # Project dependencies
└── README.md              # You're here!
📸 Demo
Here’s a quick look at the app interface:
![Screenshot_2025-04-15-10-31-02-53_99c04817c0de5652397fc8b56c3b3817](https://github.com/user-attachments/assets/15c3fcff-1885-4a54-99fa-6eabea69215e)
![Screenshot_2025-04-15-10-31-28-40_99c04817c0de5652397fc8b56c3b3817](https://github.com/user-attachments/assets/c2bef1f4-dbac-4cd7-8d16-40c4f155c7c3)



Author
Rokia Yasser
Machine Learning Engineer |[ LinkedIn](https://www.linkedin.com/in/rokia-yasser-1a8a4922b/)

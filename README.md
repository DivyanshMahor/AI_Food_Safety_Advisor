# 🥗 AI Food Safety Advisor

> Know your food before you eat it — instantly with AI.

AI Food Safety Advisor is a machine learning-based intelligent web application that detects food type and evaluates its freshness using deep learning models and smart safety logic.

It helps users understand whether food is **Safe to Eat, Eat Soon, or Not Safe** based on image analysis and environmental factors.

---

## ✨ Features

- 🍎 Food detection using CNN (MobileNetV2)
- 🦠 Spoilage detection (Fresh vs Mold)
- ⏱️ Shelf-life prediction using ML regression
- 🧠 Intelligent safety decision system
- 📊 Confidence score visualization
- 🌐 Interactive Streamlit web interface

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- CNN (MobileNetV2)
- Scikit-learn (Random Forest)
- Streamlit
- NumPy, Pandas

---

## 🧠 How It Works

1. User uploads a food image  
2. AI detects food type using CNN model  
3. Spoilage detection model checks freshness  
4. User provides time & storage conditions  
5. System predicts:
   - 🟢 Safe to Eat  
   - 🟡 Eat Soon  
   - 🔴 Not Safe to Eat  

---

## 📂 Project Structure
app.py → Streamlit UI
food_model.py → Food classification model
spoilage_model.py → Fresh vs Mold detection
regression.py → Shelf-life prediction
image_downloader.py → Dataset helper
models/ → Trained ML models
dataset/ → Training data
requirements.txt → Dependencies


---

## 🚀 How to Run

### 1. Install dependencies
pip install -r requirements.txt

2. Run application
streamlit run app.py
3. Open in browser
http://localhost:8501
⚠️ Limitations
Dataset size is limited
Accuracy depends on image quality
Some foods may be misclassified
🎯 Future Improvements
🌍 Deploy on cloud (Streamlit Cloud / AWS)
📱 Mobile app version
🧠 Improve dataset with more food classes
🔔 Food expiry reminder system
🛒 Grocery integration system

👨‍💻 Developer
Name: Divyansh Mahor
Project: AI Food Safety Advisor
Type: AI / Machine Learning Web App

⭐ Goal
To reduce food waste and improve food safety awareness using AI.


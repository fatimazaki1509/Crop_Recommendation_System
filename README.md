 <img width="1883" height="920" alt="Screenshot 2025-09-11 182805" src="https://github.com/user-attachments/assets/a161b08a-3142-49c4-9e0c-dcdfb20605b5" />
<img width="1919" height="927" alt="Screenshot 2025-09-11 182712" src="https://github.com/user-attachments/assets/b4dbcc1c-820c-4d2f-8b25-2648c9900469" />

# 🌱 Crop Recommendation System  

An AI-powered **Crop Recommendation System** built using **Machine Learning** and deployed with **Flask**.  
This system predicts the most suitable crop to grow based on soil and weather conditions like **N, P, K values, temperature, humidity, pH, and rainfall**.  

---

## 📌 Features
- Predicts best crop for given environmental conditions  
- Uses **Machine Learning (Random Forest/Decision Tree/Naive Bayes etc.)**  
- Flask-based **web app with interactive UI**  
- Scalable and extendable for real-world agricultural use  

---

## 🛠️ Tech Stack
- **Python 3.10**  
- **Flask** (for web app)  
- **scikit-learn** (ML model)  
- **pandas, numpy** (data processing)  
- **HTML, CSS** (frontend templates)  

---

## 🚀 Installation & Setup  

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/crop-recommendation.git
cd crop-recommendation
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Flask app
```bash
python app.py
```

### 4️⃣ Open in browser
```
http://127.0.0.1:5000/
```

---

## 📊 Dataset
- Sourced from Kaggle: [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)  
- Features:
  - Nitrogen, Phosphorus, Potassium  
  - Temperature, Humidity, pH, Rainfall  

---

## 📂 Project Structure
```
├── CropRecommendation.ipynb   # Model training & evaluation
├── app.py                     # Flask web app
├── model.pkl                  # Trained ML model
├── standscaler.pkl            # Standard Scaler
├── minmaxscaler.pkl           # Min-Max Scaler
├── templates/
│   └── index.html             # Web UI
├── static/                    # (Optional: CSS, JS, Images)
├── requirements.txt           # Dependencies
└── README.md                  # Project documentation
```

---

## 🎯 Future Scope
- Deploy on **Heroku / Render / AWS**  
- Add **mobile app interface**  
- Integrate **real-time weather APIs**  
- Multi-language support for farmers  

---

## 🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.  

---

## 📜 License
This project is licensed under the MIT License.  

---



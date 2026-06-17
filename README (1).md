# 🔥 AI Phishing Email Detection System

An AI-powered phishing email detection system built using Python, Flask, and Scikit-learn.  
This project detects phishing emails by analyzing email content, URLs, and suspicious keywords using machine learning and NLP techniques.

---

# 🚀 Features

✅ Detects phishing and safe emails  
✅ Machine Learning based prediction  
✅ TF-IDF text feature extraction  
✅ URL analysis  
✅ Suspicious keyword detection  
✅ Flask web application  
✅ Confusion matrix generation  
✅ Accuracy evaluation  
✅ Real-time email analysis  

---

# 🧠 Technologies Used

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Joblib

---

# 📂 Project Structure

```bash
phishing_detection_system/
│
├── app.py
├── train_model.py
├── emails.csv
├── phishing_model.pkl
├── vectorizer.pkl
├── confusion_matrix.png
│
├── templates/
│   └── index.html
│
└── .venv/
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone <repository-link>
```

---

## 2️⃣ Open Project Folder

```bash
cd phishing_detection_system
```

---

## 3️⃣ Install Required Libraries

```bash
pip install pandas scikit-learn flask matplotlib numpy joblib
```

---

# ▶️ Run the Project

## Train AI Model

```bash
python train_model.py
```

---

## Run Flask Website

```bash
python app.py
```

---

# 🌐 Open Website

Open browser and visit:

```bash
http://127.0.0.1:5000
```

---

# 📊 Model Features

The system analyzes:

- Email text content
- URLs inside emails
- Suspicious keywords
- NLP text patterns

---

# 🧪 Example Phishing Email

```text
Urgent! Verify your bank account immediately http://fakebank.com
```

---

# 🧪 Example Safe Email

```text
Team meeting tomorrow at 2 PM
```

---

# 📈 Output

The system classifies emails as:

- ⚠️ PHISHING EMAIL DETECTED
- ✅ SAFE EMAIL

---

# 🎯 Future Improvements

- Deep Learning integration
- Sender reputation analysis
- Email attachment scanning
- Real-time email inbox monitoring
- Advanced UI design
- Cloud deployment

---

# 👩‍💻 Author

Samyuktha

---

# 📜 License

This project is for educational and cybersecurity learning purposes.
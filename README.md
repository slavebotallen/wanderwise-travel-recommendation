# 🌍 Wanderwise – AI-Powered Travel Recommendation System

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=render)](https://wanderwise-travel-recommendation-g90r.onrender.com)
[![GitHub repo](https://img.shields.io/badge/GitHub-Repo-black?style=for-the-badge&logo=github)](https://github.com/<your-username>/wanderwise-travel-recommendation)

## 📖 Overview
Wanderwise is a **Personalized Travel Recommendation System** built with **Flask, scikit-learn, and Bootstrap**, deployed on **Render**.  
It helps travelers quickly discover destinations tailored to their **preferences, family size, and travel season** — reducing confusion and decision fatigue.

---

## ✨ Features
- 🔍 **Personalized recommendations** using a hybrid ML model  
- 👨‍👩‍👧 Handles **family details** (adults & children)  
- 🌦 Filters suggestions by **best season to visit**  
- 🎨 **Modern responsive UI** with Bootstrap + custom CSS  
- 🚀 Live deployment with **Render (Dockerized)**  

---

## 🧑‍💻 Tech Stack
- **Backend:** Flask, Python, Pandas, NumPy, scikit-learn  
- **Frontend:** HTML, Jinja2, Bootstrap, Custom CSS  
- **Deployment:** Docker, Render  
- **Data:** CSV datasets (`Expanded_Destinations.csv`, `UserHistory.csv`)  

---

## 📊 Methodology
Wanderwise uses a **hybrid recommendation approach**:
1. **Collaborative Filtering** → Finds similar users & suggests what they liked  
2. **Content-Based Filtering** → Matches user input with destination attributes  
3. **Hybrid Scoring** → Combines both for balanced results  

---

## 📷 Screenshots

| Input Form | Recommendations Page |
|------------|----------------------|
| ![Input Form](static/screenshots/form.png) | ![Results Page](static/screenshots/results.png) |

---

## 🎥 Demo Video
📺 A 7-minute video presentation + demo will be included in the submission.  

---

## 🛠️ Setup Instructions

Clone the repo and run locally:

```bash
git clone https://github.com/<your-username>/wanderwise-travel-recommendation.git
cd wanderwise-travel-recommendation
pip install -r requirements.txt
python app.py
```

Visit: `http://127.0.0.1:5000/`

---

## 📂 Project Structure
```
wanderwise-travel-recommendation/
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   ├── recommendation.html
├── static/
│   ├── style.css
│   ├── screenshots/
│       ├── form.png
│       └── results.png
├── dataset/
│   ├── Expanded_Destinations.csv
│   └── UserHistory.csv
├── model.pkl
├── label_encoders.pkl
├── Procfile
├── Dockerfile
└── README.md
```

---

## 📈 Results & Observations
- ✅ Recommendations are **personalized** and relevant  
- ✅ System adapts for **family-friendly trips** when children are added  
- ✅ Quick response time, scalable with more data  

---

## 📝 Future Improvements
- 💰 Add **budget & activity filters**  
- 🌐 Integrate real-time **weather & event APIs**  
- 🤖 Experiment with **deep learning recommenders**  
- 🗄️ Use a **database backend** (Postgres/Mongo) for scalability  

---

## ---
### 👤 Author

**Rithik Srivastava** 📧 Email: 24082046@scale.iitrpr.ac.in

👨‍🎓 Student Code: IITRPRAI\_24082046

🏛️ College: Indian Institute of Technology, Ropar

---

## 🌐 Live Project
👉 **[Wanderwise on Render](https://wanderwise-travel-recommendation-g90r.onrender.com)**

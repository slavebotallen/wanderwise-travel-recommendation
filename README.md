# 🌍 Wanderwise – AI-Powered Travel Recommendation System

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=render)](https://wanderwise-travel-recommendation-g90r.onrender.com)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-black?style=for-the-badge&logo=github)](https://github.com/slavebotallen/wanderwise-travel-recommendation)

## 📖 Overview
**Wanderwise** is a machine learning-powered **travel recommendation web app** that suggests destinations based on **user preferences, family size, and season**.  
Built with **Flask, scikit-learn, and Bootstrap**, and deployed on **Render** for easy access.  

---

## 🎯 Key Features
- 🎯 **Personalized travel recommendations** based on group size, children, and preferences.  
- 👨‍👩‍👧 **Family-friendly suggestions** for trips with children.  
- 🌦 **Season-aware recommendations** to ensure the best travel experience.  
- 🖥️ **Responsive UI** built with Bootstrap.  
- 🚀 **Publicly deployed** with Docker + Render.  

---

## 🧩 Tech Stack

| Component              | Technology Used                  |
|-----------------------|---------------------------------|
| Backend               | Python, Flask                   |
| Machine Learning      | scikit-learn                    |
| Frontend              | HTML, CSS, Bootstrap, Jinja2    |
| Deployment            | Docker, Render                  |
| Dataset               | Custom CSV files (`Expanded_Destinations.csv`) |

---

## 🧠 Model Architecture
- **Content-Based Filtering**: Matches user inputs to destination attributes.  
- **Collaborative Filtering**: Suggests destinations based on similar users.  
- **Hybrid Scoring Engine**: Combines both methods for better diversity and accuracy.  

---

## 📂 Project Structure
```

wanderwise-travel-recommendation-master/
├── app.py
├── requirements.txt
├── Dockerfile
├── Procfile
├── README.md
│
├── templates/
│   ├── index.html
│   ├── recommendation.html
│
├── static/
│   ├── Travel Agency Logo Advert.mp4
│   └── screenshots/
│       ├── form.png
│       ├── results.png
│
├── code and dataset/
│   ├── Expanded_Destinations.csv
│   ├── Final_Updated_Expanded_Reviews.csv
│   ├── Final_Updated_Expanded_UserHistory.csv
│   ├── Final_Updated_Expanded_Users.csv
│   ├── Travel_Recommendation_System.ipynb
│   ├── final_df.csv
│   ├── model.pkl
│   └── label_encoders.pkl
└── .gitignore

````

---

## ⚙️ Installation & Setup
Clone this repo and set up locally:

```bash
git clone https://github.com/slavebotallen/wanderwise-travel-recommendation.git
cd wanderwise-travel-recommendation-master

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py
````

Visit `http://127.0.0.1:5000/` to test locally.

---

## 🚀 Deployment on Render

1. Fork this repo and connect it to [Render](https://render.com).
2. Set **Start Command**: `gunicorn app:app`.
3. Render auto-installs dependencies from `requirements.txt`.
4. Deploy and share your live link.

---

## 📷 Screenshots

| Input Form                           | Recommendations                            |
| ------------------------------------ | ------------------------------------------ |
| ![Form](static/screenshots/form.png) | ![Results](static/screenshots/results.png) |

---

## 📊 Results & Observations

* ✅ Accurate, personalized recommendations
* ✅ Intelligent filtering for family travel
* ✅ Smooth UI and deployment performance

---

## 📝 Future Work

* 💰 Add **budget and activity-based filters**
* 🌦 Integrate **real-time weather and events** APIs
* 🤖 Experiment with **deep learning models**
* 🗄️ Migrate to a database-backed system (Postgres/MongoDB)
* 📱 Build a **Progressive Web App (PWA)**

---

## 👤 Author

**Rithik Srivastava**
📧 [24082046@scale.iitrpr.ac.in](mailto:24082046@scale.iitrpr.ac.in)
🏛️ Indian Institute of Technology, Ropar

---

## 🌐 Live Project

👉 [**Try Wanderwise Here**](https://wanderwise-travel-recommendation-g90r.onrender.com)

```

---


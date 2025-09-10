# 🌍 Wanderwise – AI-Powered Travel Recommendation System

[![Live Demo](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=render)](https://wanderwise-travel-recommendation-g90r.onrender.com)
[![GitHub repo](https://img.shields.io/badge/GitHub-Repo-black?style=for-the-badge&logo=github)](https://github.com/slavebotallen/wanderwise-travel-recommendation)

Wanderwise is a **Personalized Travel Recommendation System** built with **Flask, scikit-learn, and Bootstrap**, deployed on **Render**.  
It helps travelers quickly discover destinations tailored to their **preferences, family size, and travel season** — reducing confusion and decision fatigue.

---

## ✨ Features
- 🔍 Personalized recommendations using a **hybrid ML model**  
- 👨‍👩‍👧 Handles **family details** (adults & children)  
- 🌦 Suggests destinations based on **best season to visit**  
- 🎨 Modern responsive **UI** with Bootstrap + custom CSS  
- 🚀 Deployed publicly on **Render (Dockerized)**  

---

## 🧑‍💻 Tech Stack
- **Backend:** Flask, Python, Pandas, NumPy, scikit-learn  
- **Frontend:** HTML, Jinja2, Bootstrap, CSS  
- **Deployment:** Docker, Render  
- **Data:** CSV datasets in `code and dataset/`  

---

## 📊 Methodology
The system uses a **hybrid recommendation model**:
1. **Collaborative Filtering** – Suggests based on similar users’ preferences  
2. **Content-Based Filtering** – Matches user input with destination attributes  
3. **Hybrid Scoring** – Combines both for more accurate results  

---

## 📂 Project Structure
```
wanderwise-travel-recommendation/
├── app.py
├── requirements.txt
├── Dockerfile
├── Procfile
├── templates/
│   ├── index.html
│   ├── recommendation.html
├── static/
│   ├── screenshots/
│   │   ├── form.png
│   │   ├── results.png
│   ├── Travel Agency Logo Advert.mp4
├── code and dataset/
│   ├── Expanded_Destinations.csv
│   ├── Final_Updated_Expanded_Reviews.csv
│   ├── Final_Updated_Expanded_UserHistory.csv
│   ├── Final_Updated_Expanded_Users.csv
│   ├── Travel_Recommendation_System.ipynb
│   ├── final_df.csv
│   ├── model.pkl
│   ├── label_encoders.pkl
└── README.md
```

---

## 📷 Screenshots
| Input Form | Recommendations |
|------------|-----------------|
| ![Form](static/screenshots/form.png) | ![Results](static/screenshots/results.png) |

---

## 🎥 Demo Video
📺 A 7-minute **presentation + demo video** is included in the submission folder.  

---

## 🛠️ Setup Instructions
Clone and run locally:

```bash
git clone https://github.com/slavebotallen/wanderwise-travel-recommendation.git
cd wanderwise-travel-recommendation
pip install -r requirements.txt
python app.py
```

Visit: `http://127.0.0.1:5000/`

---

## 📈 Results & Observations
- ✅ Personalized and relevant recommendations  
- ✅ Adapts for family trips (when children added)  
- ✅ Clean, responsive interface  
- ✅ Fast results  

---

## 📝 Future Work
- 💰 Add **budget/activity filters**  
- 🌦 Integrate **real-time weather APIs**  
- 🤖 Use advanced **deep learning recommenders**  
- 🗄️ Scale with **Postgres/MongoDB**  

---

## About Me
### 👤 Author

**Rithik Srivastava** 

📧 Email: 24082046@scale.iitrpr.ac.in

👨‍🎓 Student Code: IITRPRAI_24082046

🏛️ College: Indian Institute of Technology, Ropar 

---

## 🌐 Live Project
👉 **[Try Wanderwise on Render](https://wanderwise-travel-recommendation-g90r.onrender.com)**

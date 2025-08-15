# OL-25-LP-006
A Stream lit app made by me on the analysis of mental health wellness of the tech workers backed by the OSMI dataset of 2014.
# 🌊 MindSurf: Riding the Waves of Mental Wellness in Tech 🧠💙

Welcome aboard **MindSurf**, a data-driven voyage into the mental wellness seas of the tech industry.  
This isn’t just another machine learning project—it’s an empathy engine wrapped in code.  
Our mission? To spot the silent struggles, amplify supportive voices, and give HR teams the tools to create calmer, kinder workplaces. 🏄‍♀️🌅

---

## 📖 Story Time
Once upon a sprint cycle, **NeuronInsights Analytics** was called upon by a coalition of forward-thinking tech giants—**CodeLab**, **QuantumEdge**, and **SynapseWorks**.  

They were worried: burnout, quiet quitting, and mental health challenges were spreading faster than a Friday bug fix.  
They needed a hero. Or rather… **you**—a Machine Learning Engineer with the superpower to turn messy survey data into life-changing insights.

---

## 🎯 The Grand Mission

### 🧩 Classification Quest
* **Goal:** Predict whether a techie is likely to seek mental health treatment  
* **Why:** Early detection means timely support 🌱  
* **Magic Tools:** Logistic Regression, Random Forest, XGBoost, SVM  
* **Scoreboard:** Accuracy, ROC-AUC, F1 Score  

---

### ⏳ Regression Adventure
* **Goal:** Predict a person’s **age** based on workplace vibes and personal experiences  
* **Why:** Age-targeted support is like tailoring a wetsuit—fits better, works better 🏄  
* **Magic Tools:** Linear Regression, Random Forest Regressor, XGBoost Regressor  
* **Scoreboard:** RMSE, MAE, R²  

---

### 🧭 Clustering Expedition
* **Goal:** Segment employees into mental health personas  
* **Why:** Not all heroes wear the same cape—tailored HR policies help everyone shine ✨  
* **Magic Tools:** KMeans, DBSCAN, Agglomerative Clustering  
* **Scoreboard:** Silhouette Score  

Example personas we found:  
💬 *Open Advocates* — Happy to talk, just need the platform  
🤫 *Silent Sufferers* — Carrying invisible weights  
🛠 *Under-Supported Professionals* — Willing, but waiting for help  

---

## 🗂 Dataset
* **Source:** [OSMI - Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)  
* **Size:** 1,500+ responses from tech professionals  
* **Features:**  
  - Demographics (age, gender, country)  
  - Workplace environment (benefits, leave policies)  
  - Mental health history and openness to discussing it  
  - Perceived employer support  

---

## 🖥️ Streamlit Dashboard
Our interactive Streamlit app lets you:
- Explore EDA visualizations 📊
- Input details to predict treatment likelihood 💡
- Estimate age from workplace attributes 🎂
- View mental health personas in a cluster map 🗺️

---

## ⚙️ How to Run Locally
```bash
# 1️⃣ Clone this repo
git clone https://github.com/yourusername/mindsurf.git
cd mindsurf

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run the app
streamlit run app.py

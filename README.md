# 🏏 IPL Score Predictor

This Streamlit web application predicts the **total runs** a team might score in an IPL match based on current match statistics such as runs, wickets, and overs.


---

## 📌 Features

- Predict total score during an ongoing match.
- Select teams, input current stats, and get score predictions instantly.
- Interactive and easy-to-use UI built with **Streamlit**.

---

## 🧠 Algorithms Used

- Linear Regression  
- K-Nearest Neighbor Regressor  
- XGBoost Regressor  
- Random Forest Regressor  
- Support Vector Regressor (SVR)  
- Decision Tree Regressor  

---

## ⚙️ Hyperparameter Optimization

- Utilized **Optuna** for efficient parameter tuning across all models.

---

## 📂 Dataset Information

The dataset consists of ball-by-ball match details from **2008 to 2020**.

**Dataset used:** `ipl_data.csv`

| Column            | Description                            |
|-------------------|----------------------------------------|
| `mid`             | Match ID                               |
| `date`            | Match date                             |
| `venue`           | Match venue                            |
| `bat_team`        | Batting team                           |
| `bowl_team`       | Bowling team                           |
| `batsman`         | Current batsman                        |
| `bowler`          | Current bowler                         |
| `runs`            | Current total runs                     |
| `wickets`         | Current total wickets                  |
| `overs`           | Overs completed                        |
| `run_last_5`      | Runs in last 5 overs                   |
| `wicket_last_5`   | Wickets in last 5 overs                |
| `stricker`        | Striker batsman                        |
| `non-striker`     | Non-striker batsman                    |
| `total`           | Total score (Target variable)          |


![IPL Score Predictor Demo](streamlit_app/ipl_score_predictor.gif)

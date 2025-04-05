# 🏈 Ctrl + Alt + Defeat – Behavioral Data Science II Final Project

**Because debugging is just a way of life.**

## 📅 Date: 04/04/2025  
**Course**: Behavioral Data Science II  
**Group Name**: Ctrl + Alt + Defeat  
**Team Members**: Connor Pickett, Kenadi, Lorenzo  
**Emails**:  
- kenadi.pearson@utexas.edu  
- connor.pickett@utexas.edu  
- LorenzoFlores109@gmail.com

---

## 🔮 Project Summary

What if your football team’s performance depended on the stars?  
Our project investigates whether horoscope compatibility between NFL quarterbacks (QBs) and wide receivers (WRs) has any measurable impact on their seasonal performance. 

We analyze duos based on:
- **Catchable Target Rate**
- **Target Share**
- **Receiving Yards**
- **Touchdown Share**

By calculating each player’s zodiac sign from their birthday and comparing performance metrics, we aim to test whether horoscope compatibility correlates with on-field synergy.

---

## 🧠 Machine Learning Approach

To explore this unconventional hypothesis, we apply machine learning models to classify and predict horoscope pairings using performance metrics:

- **Logistic Regression**: To assess if certain pairings outperform others significantly.
- **Support Vector Machine (SVM)**: To test whether horoscope-based groupings can be separated in feature space.
- **Principal Component Analysis (PCA)**: Optional dimensionality reduction to visualize and explore grouping patterns.

If the models can predict or classify horoscope pairs above chance, it could suggest that the stars might just play a role in WR-QB dynamics.

---

## 📊 Dataset

We use the [`nfl-data-py`](https://pypi.org/project/nfl-data-py/) Python package, which includes:
- **Roster data**: Player birthdays and positions
- **Seasonal performance data**: Key metrics used in model training

> **Dataset Shapes**:  
> - Roster Data: (5248, 37)  
> - Season Stats: (1168, 58)

---

## ❓ Key Research Questions

1. Can horoscope compatibility predict performance metrics for WR-QB duos?
2. Can a machine learning model classify horoscope pairings using WR performance data?
3. Are certain zodiac pairings more "football-compatible" than others?

---

## 🛠️ Tools & Deliverables

- ✅ GitHub Repository: [2025_FinalProject_Ctrl-Alt-Defeat](https://github.com/connor-pickett/2025_FinalProject_Ctrl-Alt-Defeat.git)  
- ✅ Jupyter Notebook with code, analysis, and figures  
- ✅ APA-style final report (10 pages)  
- ✅ PowerPoint presentation summarizing insights  
- ✅ 20-minute in-class presentation  

---

## 🚀 Get Started

Install the required libraries:

```bash
pip install nfl-data-py pandas numpy matplotlib seaborn scikit-learn

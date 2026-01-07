# Online-Gaming-Behavior-Analytics

## 📌 Project Overview

---

## 📂 Dataset Information

**Source:**
🔗 [[https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset](https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset)]

**Description:**
The Online Gaming Behavior Insights Dataset provides a comprehensive view of player behavior patterns across different demographics, game genres, and engagement levels. This dataset is designed to support exploratory data analysis, behavioral analytics, and predictive modeling related to online gaming habits. It captures how players interact with games in terms of playtime, session frequency, difficulty preference, progression, and engagement intensity.

With over 40,000 player records, this dataset is suitable for both beginner and advanced data science tasks, including visualization, clustering, classification, and behavioral trend analysis.

---

## 🧾 Column Description

| Column Name               | Description                                                           |
| ------------------------- | --------------------------------------------------------------------- |
| PlayerID                  | Unique identifier assigned to each player                             |
| Age                       | Age of the player (numeric)                                           |
| Gender                    | Gender of the player (Male / Female)                                  |
| Location                  | Geographical region of the player (e.g., USA, Europe, Other)          |
| GameGenre                 | Preferred game genre (Action, Strategy, Sports, etc.)                 |
| PlayTimeHours             | Total hours spent playing games                                       |
| InGamePurchases           | Indicates whether the player made in-game purchases (0 = No, 1 = Yes) |
| GameDifficulty            | Preferred difficulty level (Easy, Medium, Hard)                       |
| SessionsPerWeek           | Average number of gaming sessions per week                            |
| AvgSessionDurationMinutes | Average duration of each gaming session in minutes                    |
| PlayerLevel               | Current progression level of the player                               |
| AchievementsUnlocked      | Total number of achievements unlocked by the player                   |
| EngagementLevel           | Overall engagement classification (Low, Medium, High)                 |

---

## 🔍 Analysis Workflow

### 1. Data Visualization

Key questions explored:

* What is the age and gender distribution of players in the dataset?

* Which game genres are most preferred by players?

* How does player age and gender vary across different engagement levels?

* How does engagement level differ across geographical locations?

* How does total play time (PlayTimeHours) relate to player engagement level?

* Is a higher number of sessions per week associated with higher engagement?
  
* How does average session duration differ across engagement levels?

* How does preferred game difficulty relate to player engagement?

* How does engagement level differ between players who make in-game purchases and those who do not?

* How does player level vary across different engagement levels?

* Is there a relationship between the number of achievements unlocked and engagement level?

### 2. Predictive Modeling

* Logistic Regression 
* Random Forest 

---

## 🤖 Machine Learning Results

### Logistic Regression

* Accuracy: ~78%

### Random Forest (Tuned)

* Accuracy: ~91%

---

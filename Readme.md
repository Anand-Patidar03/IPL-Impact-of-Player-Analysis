# 🏏 IPL Impact Player Analysis

## 📌 Overview

This project analyzes IPL ball-by-ball data to identify the most impactful batters using a data-driven approach. Instead of relying on traditional metrics like total runs or average, this analysis combines multiple performance indicators to evaluate a player’s true contribution to the game.

---

## 🎯 Problem Statement

Traditional cricket metrics such as runs, average, and strike rate provide limited insights into a player’s true performance. This project aims to identify the most impactful IPL batters by combining scoring efficiency, consistency, and match contribution into a unified impact score.

---

## 📊 Dataset

The dataset consists of ball-by-ball IPL match data, including information such as:

* Batter name
* Runs scored
* Match identifiers
* Dismissals
* Valid deliveries

This granular data enables detailed player-level analysis.

---

## ⚙️ Approach

### 🔹 Data Processing

* Aggregated ball-by-ball data to batter level
* Handled valid deliveries and dismissals correctly

### 🔹 Feature Engineering

Created key performance metrics:

* **Strike Rate** → Scoring efficiency
* **Average** → Consistency
* **Runs per Match** → Overall contribution
* **Contribution %** → Share of team runs
* **Consistency (CV)** → Performance stability

---

## 🧠 Impact Model

An **Impact Score** was developed by combining normalized metrics:

* Strike Rate
* Average
* Runs per Match
* Consistency

This provides a holistic evaluation of player performance.

---

## 📈 Key Analysis

### 🔹 Player Role Segmentation

Batters were categorized into:

* **Elite** → High average & high strike rate
* **Aggressive** → High strike rate, lower consistency
* **Anchor** → High average, lower strike rate
* **Average / Weak** → Moderate or low performance

### 🔹 Visual Analysis

* Scatter plots to identify player roles
* Bar charts for top performers
* Contribution and consistency comparisons

---

## 🔍 Key Insights

* High strike rate alone does not guarantee high impact
* Anchors contribute more consistently to team totals
* Aggressive players often have higher impact but lower consistency
* Elite players are those who balance both scoring rate and stability

---

## 🏁 Conclusion

This project shows that a multi-metric approach provides a more accurate evaluation of player performance in T20 cricket. The impact score helps identify players who truly influence match outcomes rather than just accumulating statistics.

---

## 🚀 Future Improvements

* Incorporate match context (chasing vs setting target)
* Add phase-wise analysis (powerplay, middle overs, death overs)
* Include opposition strength and venue effects

---

## 🛠️ Tech Stack

* Python
* Pandas
* Matplotlib

---

## 📁 Project Structure

```
IPL-Impact-Analysis/
│
├── data/
|   |_ ipl.csv
├── notebooks/
│   └── IPL_Impact_Analysis.ipynb
├── images/
├── README.md

```

---

## ⭐ Key Highlight

> Developed a custom **Impact Score Model** to evaluate IPL batters beyond traditional statistics.

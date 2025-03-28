<p align="center">
  <img src="images/banner.png" alt="Red Sox EDA Banner" width="100%"/>
</p>

<h1 align="center">
  ⚾️ Boston Red Sox 2024 - Exploratory Data Analysis
</h1>
<p align="center">
  <b>Moneyball-style breakdown of the 2024 Sox using advanced stats & interactive Python charts</b>
</p>

---

## 📊 Overview

Combining a curated Excel dataset of Red Sox batters with **advanced stats pulled using [pybaseball](https://github.com/jldbc/pybaseball)**, this project uses Python and Plotly to analyze:

- Offensive efficiency
- Plate discipline
- Sabermetric value (WAR, wOBA, etc.)
- Underrated vs overrated players
- Visual storytelling of team performance

---

## 📁 Data Sources

- 📝 **Excel File**: Manual player batting data (AB, AVG, HR, RBI, etc.)
- 🧠 **pybaseball API**: WAR, wRC+, BB/K, RC, wOBA, BABIP, FIP, and more

---

## 🔍 Key Visualizations & Insights

### 1. 🎯 WAR vs Home Runs (Interactive)
> 💡 A WAR over 2.0 = solid starter. Over 5.0 = All-Star level. WAR includes defense, base running, and clutch moments.

### 2. 🧠 Walk % vs Strikeout % (Interactive)
> 💡 BB% > 10% = elite discipline | K% < 20% = great contact control.

### 3. 📊 Bar Charts for Key Metrics

### Top 10 Players by WAR
![Top 10 Players by WAR](images/top10_war.png)

### Top 10 Players by OBP
![Top 10 Players by OBP](images/top10_obp.png)

### Top 10 Players by SLG
![Top 10 Players by SLG](images/top10_slg.png)

### Top 10 Players by OPS
![Top 10 Players by OPS](images/top10_ops.png)

### Top 10 Players by BB/K
![Top 10 Players by BB/K](images/top10_bb_k.png)

### Top 10 Players by RC
![Top 10 Players by RC](images/top10_rc.png)

### Top 10 Players by wOBA
![Top 10 Players by wOBA](images/top10_woba.png)

### Top 10 Players by BABIP
![Top 10 Players by BABIP](images/top10_babip.png)

### Top 10 Players by FIP
![Top 10 Players by FIP](images/top10_fip.png)


---

## 🧰 Tools & Libraries

- `pandas`, `numpy`
- `seaborn`, `matplotlib`
- `plotly` (for interactivity)
- `pybaseball` (for real MLB stat scraping)
- Google Colab

---

## 🛠 How to Use

1. Upload or modify `RedSox_2024_Batting_Stats.xlsx`
2. Run the notebook in Google Colab
3. Visuals generate automatically with insights and interactivity

---

## 👩‍💻 Author

**Katie Pleasley**  
Lover of baseball data, sabermetrics, and telling stories with stats ⚾️📊

---

## 🚀 Future Enhancements

- Add pitching and fielding stats side-by-side
- Compare to league average or league percentile
- Deploy a full dashboard (Streamlit or Dash)
- Predictive modeling using scikit-learn

---

## 🌟 Like This?

Give it a ⭐ on GitHub and share with fellow Red Sox fans or baseball data nerds!

# 📈 Video Game Investment Strategy: Global Trend Analysis (2013–2016)

## 📌 Business Context
The video game industry operates in console life cycles (platform-based ecosystems).  
The main goal of this project is to **filter historical noise** and analyze global and regional sales performance, as well as user preferences, during the **most recent and relevant period (2013–2016)**.

This analysis helps identify the platforms and genres with the **highest potential return on investment (ROI)** for future releases.

---

## 🎯 Methodology

1. **Data Cleaning and Preprocessing**
   - Column name normalization.
   - Handling missing values.
   - Standardization of the `user_score` field (converting `'tbd'` values to null).

2. **Relevant Time Period Definition**
   - Strict filtering of data from **2013 onwards** to focus on the current console life cycle  
     (e.g., PS4, Xbox One, and predecessor platforms of the Nintendo Switch).

3. **Regional Segmentation Analysis**
   - Detailed evaluation of sales performance and user preferences by:
     - **North America (NA)**
     - **Europe (EU)**
     - **Japan (JP)**
   - Analysis by genre and content rating.

4. **Statistical Inference**
   - Student’s T-test and correlation analysis to measure the real impact of:
     - **Critic scores**
     - **User scores**
   - Evaluation of their influence on global sales volume.

---

## 💡 Key Strategic Insights (Investor-Focused Results)

- **High-Return Platforms**  
  Only **[Dominant Platform]** and **[Second Platform]** showed sustained growth between 2013 and 2016, indicating that investment should prioritize these ecosystems.

- **Regional Genre Preferences**
  - **Shooter** games dominate the North American and European markets.
  - **Role-Playing Games (RPGs)** are the top priority in the Japanese market.

- **Impact of Reviews**
  Statistical analysis shows that **critic scores have a significant correlation with global sales**, while user scores do not show a strong or consistent relationship.

**Final Conclusion:**  
Investment decisions should align with the current console life cycle, and content strategies must be adapted to regional market preferences to maximize ROI.

---

## 🛠️ Technologies Used
`Python` | `Pandas` | `NumPy` | `SciPy.stats` (Statistical Inference) | `Matplotlib` | `Seaborn`

# A/B Testing of Website Themes Using Python

## 📌 Project Description

This project focuses on conducting an A/B test to compare two website themes — Light and Dark — with the goal of understanding their impact on user engagement and behavior. The key performance indicators (KPIs) analyzed include Click Through Rate (CTR), Conversion Rate, Bounce Rate, Scroll Depth, Session Duration, and Purchases. The insights help determine if a specific theme drives significantly better outcomes in terms of user interaction and conversion.

## 🧪 Project Steps

1. **Data Collection & Preparation**
   - Collected anonymized user interaction data including demographic info (Age, Location), behavioral metrics (CTR, Conversion Rate, Bounce Rate, etc.), and event flags (Added_to_Cart, Purchases).
   - Ensured data cleanliness and proper formatting for statistical analysis.

2. **Exploratory Data Analysis (EDA)**
   - Visualized key metrics (CTR, Conversion Rate, Session Duration) using scatter plots and summary statistics.
   - Identified that the relationship between CTR and Conversion Rate is consistent across both themes.

3. **Hypothesis Testing**
   - **Conversion Rate A/B Test**
     - **Null Hypothesis (H0):** No difference in Conversion Rate between Light and Dark themes.
     - **z-statistic:** 0.8531
     - **p-value:** 0.3936  
     ➤ *Result:* Not statistically significant; the slight difference in conversion rates may be due to random variation.

   - **Session Duration A/B Test**
     - **Null Hypothesis (H0):** No difference in average Session Duration between the themes.
     - **t-statistic:** 0.3528
     - **p-value:** 0.7243  
     ➤ *Result:* Not statistically significant; average session durations are very similar.

4. **Interpretation**
   - Both Conversion Rate and Session Duration do not show statistically significant differences between the two themes.
   - Click Through Rate is consistent with Conversion Rate, implying stable behavior patterns irrespective of initial interest.

## ✅ Conclusion

The A/B test results suggest that:
- There is no statistically significant difference in Conversion Rate or Session Duration between the Light and Dark themes.
- The user behavior remains consistent across themes, and variations in performance metrics are likely due to randomness rather than theme-driven influence.

🔍 **Key Takeaway:**  
No theme showed superior performance, so either theme can be adopted based on aesthetic preference or brand alignment without negatively impacting user metrics.

---

## 🛠 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **SciPy / Statsmodels**
- **Jupyter Notebook**

---

## Data Viz 
<img width="642" alt="1" src="https://github.com/user-attachments/assets/0ad4eea8-1201-453b-8c54-dfa6597a82bd" />

<img width="665" alt="2" src="https://github.com/user-attachments/assets/d27e12f9-bd55-4978-b997-16fe86271f0e" />

<img width="683" alt="3" src="https://github.com/user-attachments/assets/35387817-8db9-47c1-bccc-c590cd460f7b" />

<img width="686" alt="4" src="https://github.com/user-attachments/assets/ce1a54bc-76a6-43bc-9356-769f11a7ae9a" />

<img width="493" alt="5" src="https://github.com/user-attachments/assets/8255e6a0-b0c3-4431-8c20-cd44fcd7056b" />

<img width="559" alt="6" src="https://github.com/user-attachments/assets/97dfac05-c56f-446b-b5f9-9877a8db0725" />

## 📈 Next Steps

- Test theme impact on other conversion metrics like "Add to Cart" or "Purchases".
- Conduct segmented analysis based on Age and Location.
- Run longer experiments for more conclusive results.


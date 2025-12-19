# Revenue Optimization for Transport Services  
### Payment Behavior Analysis using Python & Hypothesis Testing

## 📌 Project Description
This project analyzes large-scale taxi trip data to understand how payment methods influence fare amounts and overall driver revenue. Using statistical analysis and hypothesis testing, the study investigates whether customers paying via credit cards generate higher revenue compared to cash payments.

The goal is to provide data-driven recommendations that help transport platforms and drivers optimize revenue without negatively impacting customer experience.

---

## 🎯 Business Problem
In the competitive taxi and transport services industry, maximizing driver revenue is critical for long-term sustainability and driver satisfaction.  
The key question addressed in this project is:

**Does payment type (credit card vs cash) significantly impact fare amounts and revenue generation?**

---

## 📊 Dataset Overview
- Scale: **6 million+ taxi trip records**
- Domain: Transport / Taxi Services
- Data type: Structured trip-level transactional data

### Key Features Used
- `payment_type` (Card / Cash)
- `fare_amount`
- `trip_distance` (miles)
- `trip_duration` (minutes)
- `passenger_count`

---

## 🛠 Tools & Technologies
- Python
- Pandas & NumPy
- SciPy (Hypothesis Testing)
- Statistics
- Matplotlib & Seaborn
- Jupyter Notebook

---

## 🔍 Methodology
1. **Data Cleaning & Feature Selection**  
   Focused on relevant columns impacting revenue and payment behavior.

2. **Descriptive Analysis**  
   Compared average fare amount and trip distance across payment types.

3. **Hypothesis Testing (T-Test / A/B Testing)**  
   - **Null Hypothesis (H₀):** No difference in average fare between card and cash payments  
   - **Alternative Hypothesis (H₁):** A significant difference exists between the two payment methods

4. **Statistical Validation**  
   Used T-test to evaluate the statistical significance of fare differences.

---

## 📈 Key Findings
- Card payments account for **~67.5%** of all taxi transactions
- Customers paying by card show:
  - Higher average fare amounts
  - Slightly longer trip distances
- T-test results:
  - **T-statistic ≈ 165**
  - **P-value < 0.05**
  - Result: **Null hypothesis rejected**
- Payment type has a **statistically significant impact** on fare amounts

---

## 💡 Business Insights
- Customers prefer card payments for higher-value and longer trips
- Card-paying customers contribute more revenue per trip
- Single-passenger trips dominate both card and cash transactions, but card usage is significantly higher

---

## ✅ Recommendations
- Encourage card payments through:
  - Driver incentives
  - In-app nudges and discounts
  - Seamless and secure digital payment options
- Promote digital payments without harming customer experience
- Use payment-based insights to design revenue-boosting strategies

📊 **Projected Impact:**  
- Estimated **~15% potential revenue increase** through optimized payment behavior

---

## 📌 Conclusion
This project demonstrates how statistical analysis and hypothesis testing can uncover actionable insights in transport services. Encouraging credit card payments can significantly increase fare revenue while maintaining customer convenience, leading to improved driver earnings and platform growth.

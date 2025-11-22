# CO2 Emissions vs. Carbon Pricing: Sweden Case Study

## 📖 Project Overview
This project evaluates the effectiveness of **Carbon Pricing** on **CO2 Emissions** in Sweden (1991–2023).

It utilizes historical data to visualize the decoupling of economic policy from environmental impact, determining if the "Polluter Pays" principle effectively drives down national emissions.

## ⚙️ Methodology
The analysis uses Python to normalize and correlate dissimilar datasets (Currency vs. Mass).

### 1. Data Normalization
* **Technique:** `MinMaxScaler` (Scikit-learn).
* **Logic:** Scales Carbon Price (€) and Emissions (Tons) to a `[0, 1]` range, allowing for direct visual comparison of trends despite different units.

### 2. Trend Logic
* **Inverse Correlation (Effective):** Price $\uparrow$ AND Emissions $\downarrow$ (Desired outcome).
* **Direct Correlation (Ineffective):** Price $\uparrow$ AND Emissions $\uparrow$ (Policy failure or external factors).

## 📊 Key Results
Sweden demonstrates a successful long-term implementation of carbon taxation.

| Trend | Observation |
| :--- | :--- |
| **Carbon Price** | Continuous upward trend from ~41€ (1991). |
| **CO2 Emissions** | Consistent downward trend (Decoupling achieved). |
| **Policy Impact** | Major price hikes correlate directly with emission drops. |

## 📈 Visualization

### Figure 1: Policy Effectiveness Trends
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/5ae4105a-8483-44ec-b39c-8504a1847ea1" />

> *Scaled comparison showing the inverse relationship between rising carbon costs (Green) and falling emissions (Black).*

## 🛠️ Tech Stack
* **Python:** `Pandas` (Time-series data), `Scikit-learn` (Preprocessing).
* **Visualization:** `Matplotlib` (Conditional fill plots).

---

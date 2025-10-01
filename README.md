# 🌍 Maji Ndogo Farm Project  
### *Unlocking Ethical Agricultural Intelligence from Integrated Field Data*

> **"When it comes to data for social impact, accuracy isn’t optional—it’s ethical."**

This project analyzes multi-source agricultural survey data from **Maji Ndogo** to understand crop performance, environmental factors, and farm management practices—**not just to find patterns, but to question them**.

## 🌱 What We’re Exploring

We’ve unified **four key datasets** into a single analytical view:
- 📍 **Geographic features** (elevation, location)
- ☀️ **Weather conditions**
- 🌱 **Soil & crop characteristics**
- 🧑‍🌾 **Farm management practices**

Using **Pandas** and **SQLite**, we clean, merge, and explore relationships between variables like:
- `Standard_yield` vs. `Pollution_level`
- Crop performance across `Soil_type`
- Data anomalies that could mislead policy or advice

---

## 🔍 Key Insights (So Far)

- ✅ **Data cleaning matters**: Fixed typos (`'cassaval' → 'cassava'`), swapped mislabeled columns, and ensured `Elevation ≥ 0`.
- 📊 **Exploratory visuals** reveal:
  - Yield variation by crop type
  - Skewed yield distributions
  - Potential pollution-yield correlations
- ⚠️ **But... are these patterns trustworthy?**  
  What if low yields reflect harsh growing conditions—not poor crops?  
  What if missing data hides the full story?

> **We refuse to act on assumptions.**  
> That’s why **Part 2** is coming…

---

## 🕵️‍♂️ Coming Soon: *“The Data Detective” (Part 2)*

In the next phase, we’ll:
- 🔗 **Validate survey data** with **real-time sensor readings** (rainfall, temperature, pollution)
- 🗺️ Map data gaps across Maji Ndogo
- 🧪 Test whether observed patterns hold up in the real world

> Because farmers deserve **truth—not just trends**.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)

---

## 📂 Project Structure

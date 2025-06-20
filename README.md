# 🌾 Climate Change Impacts on Wheat Yield: A Data Science Project

## 📘 Overview

This project investigates how **climate change**, specifically rising **temperatures** over time, is affecting **wheat crop yields** globally. Using real-world data, we apply **Polynomial Regression** to model the relationship between **average annual temperature**, **year**, and **wheat yield** for two major wheat-producing countries: **India** and the **United States**.

---

## 🎯 Objectives

- Analyze how rising temperatures and changing years affect wheat yields.
- Build country-specific regression models to capture regional effects.
- Visualize results with 2D and 3D plots for better interpretability.
- Compare model performance between India and the USA.

---

## 📁 Dataset Sources

- 🌍 Climate Data: [Kaggle - Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- 🌾 Crop Yield Data: [Kaggle - FAO Food and Agriculture Data](https://www.kaggle.com/datasets/fao-statistics/food-agriculture-data)

*Note: Dataset files were cleaned, merged, and filtered for wheat yield and temperature.*

---

## 🛠️ Technologies Used

- **Python** (Google Colab)
- **Pandas**, **NumPy** for data handling
- **Matplotlib**, **3D Plotting (Axes3D)** for visualization
- **Scikit-learn** for Polynomial Regression modeling

---

## 🔍 Project Workflow

1. **Data Cleaning & Merging**  
   Merged crop yield and temperature data by `Country` and `Year`.

2. **Feature Engineering**  
   Extracted `Avg_Temp`, `Year`, and `Wheat_Yield` features.

3. **Model Training**  
   Used 4th-degree Polynomial Regression for non-linear prediction.

4. **Evaluation & Visualization**  
   - Scatter plots of actual vs predicted yield  
   - 3D surface plots: Temperature × Year × Yield

---

## 📊 Key Results

- Polynomial models achieved strong R² values for both countries.
- Temperature and year both significantly impact wheat yield.
- India and USA show different sensitivities to climate change due to their geographical and technological differences.

---

## 📈 Sample Visuals

- ✅ Actual vs Predicted Wheat Yield (India & USA)  
- ✅ 3D Surface Plot showing climate impact  
*(Run the notebook to see plots)*

---

## 📌 How to Run

1. Clone the repository or download the notebook.
2. Upload datasets (`GlobalLandTemperaturesByCountry.csv`, `FAOSTAT_data.csv`) to your Colab/working directory.
3. Open the notebook and run all cells sequentially.

---

## 📎 Future Improvements

- Add more features: **Rainfall**, **CO₂ levels**, **Soil data**
- Expand analysis to **multiple crops** and **more countries**
- Apply **time series** or **neural network models** for forecasting

---

## 🙌 Acknowledgements

- [Kaggle Datasets](https://kaggle.com)
- [FAO](https://www.fao.org/)
- [Berkeley Earth Climate Data](http://berkeleyearth.org/)

---

## 👩‍💻 Author

**Asmi Dagar**  
*A B.tech Student & Data Science Enthusiast*  
LinkedIn: [www.linkedin.com/in/asmi-dagar-7b4441289](#) | GitHub: [](#)
---

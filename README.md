# 🌲 Algerian Forest Fire - Exploratory Data Analysis (EDA) 🔥

## 📌 Overview
This project performs an **Exploratory Data Analysis (EDA)** on the **Algerian Forest Fire Dataset** to identify patterns, correlations, and insights related to forest fires in Algeria. The goal is to understand the factors influencing fire occurrences and their intensity.

---
## 📂 Dataset Information
The dataset contains meteorological and fire-related features collected from two regions in Algeria: **Bejaia Region** and **Sidi Bel-abbes Region**. 

### 🔑 Key Attributes:
- 🌡 **Temperature (°C)**
- 💦 **Relative Humidity (%)**
- 💨 **Wind Speed (km/h)**
- 🌧 **Rainfall (mm)**
- 🌲 **Fine Fuel Moisture Code (FFMC)**
- 🍂 **Duff Moisture Code (DMC)**
- 🌵 **Drought Code (DC)**
- 🔥 **Initial Spread Index (ISI)**
- 📊 **Buildup Index (BUI)**
- ⚠ **Fire Weather Index (FWI)**
- 🏷 **Classes (Fire, No Fire)**

---
## 🎯 Objectives
✔ Analyze the **distribution** of meteorological factors.
✔ Identify **correlations** between weather conditions and fire occurrences.
✔ Visualize patterns using **data visualization techniques**.
✔ Apply **Regression Models** to predict fire index values.
✔ Provide insights that can help in **fire prevention and management**.

---
## 🔍 Steps Performed
### 1️⃣ Data Cleaning & Preprocessing
   - 🛠 Handling missing values
   - 🗂 Formatting date and categorical variables
   - 🔄 Encoding target labels
### 2️⃣ Exploratory Data Analysis (EDA)
   - 📊 Univariate & bivariate analysis
   - 🔥 Correlation heatmap
   - 📈 Distribution plots (Histograms, Boxplots, KDE)
   - 🖼 Pairwise relationships using scatter plots
### 3️⃣ Regression Modeling
   - 📌 Implemented **Linear Regression**, **Ridge Regression**, and **Lasso Regression**
   - 🔄 Performed **Cross-Validation (CV)** for model evaluation
   - 📉 Compared model performances using error metrics (**RMSE, MAE, R²**)
### 4️⃣ Visualization & Insights
   - 🎯 Feature importance in fire occurrences
   - 🌍 Influence of temperature, wind, and humidity
   - 🚨 Fire vs. No-Fire class distribution

---
## 🛠 Tools & Libraries Used
- 🐍 **Python**
- 📊 **Pandas, NumPy** (Data manipulation)
- 🎨 **Matplotlib, Seaborn** (Data visualization)
- 🤖 **Scikit-learn** (Machine learning & regression models)

---
## 🔑 Key Findings
✅ Higher temperatures and lower humidity levels significantly increase fire risks.
✅ **Fire Weather Index (FWI)** is strongly correlated with fire occurrences.
✅ Wind speed plays a crucial role in spreading fires.
✅ Certain meteorological conditions serve as **early warning indicators**.
✅ **Ridge and Lasso Regression** provided better generalization compared to standard **Linear Regression**.

---
## 🚀 Future Scope
🔹 Apply **Advanced Machine Learning models** for fire prediction.
🔹 Integrate real-time data for **early fire detection**.
🔹 Extend analysis to other regions with similar climatic conditions.

---
## 📌 How to Use
1️⃣ Clone the repository
   ```sh
   git clone https://github.com/SangamSrivastav/algerian_forest_fire_eda.git
   ```
2️⃣ Install dependencies
   ```sh
   pip install -r requirements.txt
   ```
3️⃣ Run the Jupyter Notebook to explore the analysis.

---
## 👥 Contributors
- **Sangam Srivastav**

---
## 📜 License
This project is open-source under the **MIT License**.


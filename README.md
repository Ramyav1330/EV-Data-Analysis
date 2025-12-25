# 🚗 Electric Vehicle Data Analysis

## 📌 Project Overview

This project analyzes Electric Vehicle (EV) registration data from the **Washington State Department of Licensing (DOL)**. The dataset includes Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered across different counties and cities in Washington.

The objective of this project is to:

* Clean and preprocess EV registration data
* Perform exploratory data analysis (EDA)
* Visualize adoption trends and geographic distribution
* Build a Linear Regression model to predict electric vehicle range

---

## 📊 Dataset Information

**Dataset Name:** Electric Vehicle Population Data
**Source:** Washington State Department of Licensing (DOL)

### Key Columns:

* **VIN (1-10):** Vehicle identifier (anonymized)
* **County / City / State:** Registration location
* **Model Year:** Manufacturing year
* **Make / Model:** Vehicle brand and model
* **Electric Vehicle Type:** BEV or PHEV
* **Electric Range:** Range in miles on full charge
* **Base MSRP:** Manufacturer’s suggested retail price
* **CAFV Eligibility:** Clean Alternative Fuel Vehicle eligibility
* **Vehicle Location:** GPS coordinates

---

## 🧹 Data Cleaning Steps

* Handled missing and zero values in **Base MSRP** and **Electric Range**
* Removed duplicate records
* Anonymized VIN values while maintaining uniqueness
* Extracted latitude and longitude from vehicle location data

---

## 🔍 Exploratory Data Analysis

Key insights explored:

* Top 5 EV makes and models
* EV registrations by county
* EV adoption trends across model years
* Average electric range and MSRP
* CAFV eligibility distribution
* Urban vs rural EV adoption patterns

---

## 📈 Data Visualizations

The following visualizations were created:

* Bar chart of top EV manufacturers
* Line graph showing EV adoption over time
* Scatter plot of Electric Range vs Base MSRP
* Pie chart of CAFV eligibility
* (Optional) Geospatial maps for EV distribution

---

## 🤖 Machine Learning Model

A **Linear Regression** model was built to predict **Electric Range**.

### Features Used:

* Model Year
* Base MSRP
* Vehicle Make (One-Hot Encoded)

### Model Evaluation:

* Train-test split: 80/20
* Metric used: **R² Score**
* The model shows a moderate relationship between pricing, model year, and electric range

---

## 🛠 Tools & Technologies Used

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning
* **Jupyter Notebook** – Analysis environment

---

## 📁 Repository Structure

```
EV-Data-Analysis/
│
├── EV_Data_Analysis.ipynb   # Jupyter Notebook with full analysis
├── README.md               # Project documentation
└── Electric_Vehicle_Population_Data.csv
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/EV-Data-Analysis.git
```

2. Open the Jupyter Notebook

```bash
jupyter notebook EV_Data_Analysis.ipynb
```

3. Run all cells to reproduce the analysis

---

## 📌 Conclusion

This project highlights strong EV adoption growth in urban areas, dominance of specific manufacturers like Tesla, and a clear relationship between vehicle price and electric range. The analysis can support policy decisions, infrastructure planning, and market research in the EV sector.

---

## 👩‍💻 Author

**Ramya V**

---

⭐ If you found this project useful, feel free to star the repository!

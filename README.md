# Weather Data Analysis and Visualization Using Python

## 📌 Project Overview

This project focuses on analyzing and visualizing daily weather data using Python.

The analysis explores important weather parameters such as temperature, rainfall, humidity, atmospheric pressure, and wind speed. The project uses **Pandas, NumPy, and Matplotlib** to perform data analysis and create visualizations.

The dataset used in this project contains **30 daily weather observations from January 1, 2026 to January 30, 2026** with 8 columns.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand the structure of a weather dataset
* Perform basic data inspection and statistical analysis
* Check for missing values
* Clean the dataset
* Analyze minimum and maximum temperatures
* Analyze rainfall patterns
* Analyze humidity levels
* Analyze wind-speed variation
* Study relationships between weather parameters using correlation analysis
* Visualize weather patterns using Python

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Google Colab / Jupyter Notebook**

---

## 📊 Dataset

The dataset is created directly within the Python notebook using a Pandas DataFrame.

### Dataset Details

* **Number of records:** 30
* **Number of columns:** 8
* **Date range:** January 1, 2026 – January 30, 2026

### Features

| Column         | Description                              |
| -------------- | ---------------------------------------- |
| `Date`         | Date of the weather observation          |
| `MinTemp`      | Minimum temperature                      |
| `MaxTemp`      | Maximum temperature                      |
| `Rainfall`     | Rainfall measurement                     |
| `Humidity3pm`  | Humidity recorded at 3 PM                |
| `Pressure3pm`  | Atmospheric pressure recorded at 3 PM    |
| `WindSpeed3pm` | Wind speed recorded at 3 PM              |
| `RainToday`    | Indicates whether rain occurred that day |

The notebook confirms that all 30 records contain values for each of the eight columns.

---

## 🔍 Data Analysis Process

### 1. Data Loading

The weather data is created using a Pandas DataFrame with daily observations.

### 2. Data Inspection

The project performs:

* `head()`
* `tail()`
* `shape`
* `info()`
* `describe()`

These operations are used to understand the dataset structure, data types, statistical summary, and number of observations.

### 3. Missing Value Analysis

Missing values are checked using:

```python
weather.isnull().sum()
```

The dataset contains no missing values.

The notebook also applies `dropna()` to create a cleaned dataset. The original and cleaned datasets both contain **30 rows and 8 columns**.

---

## 🌡️ Temperature Analysis

The project analyzes:

* Average maximum temperature
* Highest temperature
* Lowest temperature
* Minimum and maximum temperature variation

The calculated values include:

* **Average maximum temperature:** 31.77 °C
* **Average minimum temperature:** 20.87 °C
* **Highest temperature:** 37 °C
* **Lowest temperature:** 18 °C

The notebook also creates a line plot to visualize minimum and maximum temperature variation across the observed days.

---

## 🌧️ Rainfall Analysis

Rainfall is analyzed to understand how precipitation varies across the observed days.

The project calculates:

* Average rainfall
* Total rainfall
* Daily rainfall variation

The dataset has an average rainfall of approximately **3.97 mm**, with a total rainfall of **119 mm** across the 30 observations.

---

## 💧 Humidity Analysis

The project examines the `Humidity3pm` variable to understand changes in humidity across different days.

The calculated average humidity is:

**66.1%**

The notebook also visualizes weather-related variations to make the patterns easier to interpret.

---

## 🌬️ Wind Speed Analysis

Wind speed is analyzed using the `WindSpeed3pm` column.

The project calculates the average wind speed and visualizes its variation across the observed days.

**Average wind speed:** 17.6 km/h

---

## 📈 Correlation Analysis

A correlation matrix is created using:

* Minimum temperature
* Maximum temperature
* Rainfall
* Humidity
* Atmospheric pressure
* Wind speed

The project uses Pandas `.corr()` to calculate relationships between the numerical weather parameters.

A **correlation heatmap** is also created using Matplotlib to provide a visual representation of these relationships.

---

## 📊 Visualizations

The notebook includes visual analysis for different weather parameters, including:

* Minimum and maximum temperature variation
* Rainfall patterns
* Wind-speed variation
* Correlation heatmap
* Other weather parameter visualizations

These visualizations help make the numerical patterns easier to understand.

---

## 📌 Key Findings

Based on the analysis performed in the notebook:

1. The dataset contains daily weather observations.
2. Temperature varies across different days.
3. Humidity levels show noticeable variation.
4. Rainfall varies between different days.
5. Wind speed changes across the observations.
6. Correlation analysis helps examine relationships between weather parameters.
7. Data visualization makes weather patterns easier to understand.

---

## 📁 Project Structure

```text
weather-data-analysis-python/
│
├── README.md
├── weather_data_analysis.ipynb
└── requirements.txt
```

---

## ▶️ How to Run the Project

### Option 1: Google Colab

1. Open Google Colab.
2. Upload `weather_data_analysis.ipynb`.
3. Run the cells sequentially.

### Option 2: Jupyter Notebook

Clone or download this repository and open the notebook using Jupyter Notebook or JupyterLab.

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open:

```text
weather_data_analysis.ipynb
```

and run the cells.

---

## 📚 Skills Demonstrated

This project demonstrates practical experience with:

* Python for Data Analysis
* Pandas DataFrames
* NumPy
* Data inspection
* Missing-value checking
* Descriptive statistics
* Data visualization
* Correlation analysis
* Matplotlib
* Exploratory Data Analysis (EDA)

---

## 🚀 Future Improvements

Possible improvements for a future version include:

* Use a larger real-world weather dataset
* Add more locations
* Perform time-series analysis
* Add advanced statistical analysis
* Create interactive visualizations
* Build a weather dashboard using Power BI or another visualization platform
* Develop a weather prediction model using machine learning

---

## 👩‍💻 Project Author

**Hiniyasri P.**

This project was created as part of a learning journey in **Python, Data Analysis, and Data Visualization**.

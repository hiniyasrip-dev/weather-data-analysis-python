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

The notebook also visualizes weather-related variations

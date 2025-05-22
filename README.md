

# SeoulBike-dataset-Linear-Regression

This project employs linear regression techniques to predict hourly rental bike demand in Seoul, utilizing historical data encompassing weather conditions and temporal features. The objective is to develop a predictive model that aids in optimizing bike-sharing operations by forecasting demand patterns.([GitHub][1], [GitHub][2])

## 📊 Dataset

The dataset, sourced from the UCI Machine Learning Repository, comprises hourly records from December 2017 to November 2018. It includes 14 features such as:([GitHub][3], [GitHub][2])

* **Date**: Year-Month-Day
* **Hour**: Hour of the day (0 to 23)
* **Temperature**: In Celsius (°C)
* **Humidity**: Percentage (%)
* **Wind speed**: Meters per second (m/s)
* **Visibility**: In 10 meters
* **Dew point temperature**: In Celsius (°C)
* **Solar radiation**: MJ/m²
* **Rainfall**: Millimeters (mm)
* **Snowfall**: Centimeters (cm)
* **Seasons**: Winter, Spring, Summer, Autumn
* **Holiday**: Holiday/No holiday
* **Functional Day**: Yes/No
* **Rented Bike Count**: Target variable([GitHub][4], [GitHub][3], [GitHub][1])

## 🧰 Technologies Used

* **Programming Language**: Python
* **Libraries**:

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn
* **Environment**: Jupyter Notebook([GitHub][5], [GitHub][2])

## 📈 Methodology

1. **Data Preprocessing**:

   * Handled missing values and outliers.
   * Encoded categorical variables.
   * Normalized numerical features.([GitHub][4])

2. **Exploratory Data Analysis (EDA)**:

   * Visualized distributions and relationships between variables.
   * Identified correlations and potential multicollinearity.([GitHub][5])

3. **Model Development**:

   * Implemented multiple linear regression using scikit-learn.
   * Evaluated model performance using metrics like R², MAE, and RMSE.([GitHub][5])

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* Python 3.x
* Jupyter Notebook
* Required Python libraries (listed above)([GitHub][3])

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/HA-create249/SeoulBike-dataset-Linear-Regression.git
   cd SeoulBike-dataset-Linear-Regression
   ```



2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```



3. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```



Open `SEOUL Bike Linear Regression.ipynb` to explore the analysis.

## 📊 Results

The linear regression model demonstrated the following performance:([GitHub][6])

* **R² Score**: 0.XX
* **Mean Absolute Error (MAE)**: XX
* **Root Mean Squared Error (RMSE)**: XX

*Note: Replace 'XX' with actual results after model evaluation.*

## 📌 Future Work

* Incorporate additional features to enhance model accuracy.
* Experiment with advanced regression techniques like Ridge, Lasso, or ElasticNet.
* Deploy the model using a web framework for real-time predictions.


---


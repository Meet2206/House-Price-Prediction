# House Price Prediction with Synthetic Data

This project predicts house prices using a synthetically generated dataset. The model considers various features such as size, house type, city, area, number of rooms, and house age to estimate the property price. The pipeline includes data generation, EDA (Exploratory Data Analysis), preprocessing, model training, evaluation, and visualization.

## 📌 Features

* **Synthetic Data Generation:** Randomly generates data for different house types, cities, areas, and features.
* **Exploratory Data Analysis (EDA):** Price distribution, correlation heatmap, and data summary.
* **Preprocessing Pipeline:** Scaling for numerical features and One-Hot Encoding for categorical features.
* **Machine Learning Models:**

  * Linear Regression
  * Random Forest Regressor
* **Performance Evaluation:** MSE, R² Score
* **Visualization:** Actual vs Predicted prices comparison.

## 📊 Dataset

The synthetic dataset includes:

* **Size:** House size in square feet
* **House Type:** Flat, Bungalow, Duplex, Triplex, Tenament
* **City:** Vadodara, Ankleshwar, Surat
* **Area:** Popular areas within each city
* **Rooms:** Number of rooms
* **Age:** Age of the house
* **Price:** Calculated based on multipliers and noise

Dataset is automatically saved as:

```
synthetic_house_prices.csv
```

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```

2. **Create & activate virtual environment (optional but recommended):**

```bash
python3 -m venv myenv
source myenv/bin/activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the notebook or script**

* For Jupyter Notebook:

```bash
jupyter notebook
```

* For Python script:

```bash
python house_price_prediction.py
```

## 🧩 Requirements

* Python 3.13+
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

You can install them via:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📈 Results

Both Linear Regression and Random Forest models are trained and evaluated. The performance metrics (MSE and R² Score) along with visualizations help in understanding model accuracy.

## 📊 Visualization Example

* **Price Distribution**
* **Correlation Heatmap**
* **Actual vs Predicted Prices Plot**

## 📌 Author

**Meet Limbachiya**

## 📃 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

# 🌾 Rice Crop Yield Prediction & Protein Deficiency Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-pandas-green.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Library-seaborn-lightblue.svg)](https://seaborn.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange.svg)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project leverages *Python, Pandas, Seaborn, and Machine Learning* to analyze rice crop yield, soil conditions, and protein deficiency severity. By combining data preprocessing, predictive modeling, and visualization, it provides actionable insights and recommendations to improve rice production and address nutritional deficiencies.

---

## 📌 Features

* 🔄 **Data Preprocessing** – Cleans, structures, and converts raw agricultural data for reliable analysis.
* 📊 **Exploratory Data Analysis (EDA)** – Statistical and graphical techniques to uncover yield patterns and soil characteristics.
* 🤖 **Machine Learning Models** – Implements *Random Forest* to predict yield, protein deficiency severity, and recommend optimal rice varieties.
* 📉 **Visualization Tools** – Bar charts, pie charts, and heatmaps to illustrate factors affecting yield.
* 📝 **User Input & Prediction** – Interactive interface to input soil/environmental conditions and receive predictions.
* 💡 **Recommendation System** – Suggests fertilizers, soil management techniques, and rice varieties for better yield and reduced deficiency.

---

## ⚙ Tech Stack

* **Programming Language**: Python 3.x
* **Libraries**:

  * pandas – Data preprocessing
  * seaborn / matplotlib – Data visualization
  * scikit-learn – Machine Learning (Random Forest)

---

## 📂 Project Structure

```bash
Rice-Yield-Analysis/
│── data/
│   └── raw/
│       └── rice_yield_prediction.csv   # Raw dataset
│
│── scripts/
│   ├── Data-Collection.py              # Script for gathering agricultural data
│   ├── Data-Preprocessing.py           # Script for cleaning & preparing data
│   ├── Data-Visualization.py           # Script for EDA & visualizations
│   └── PredictionModel.py              # Machine Learning model (Random Forest)
│
│── README.md                           # Project documentation
│── requirements.txt                    # Dependencies (pandas, seaborn, sklearn, etc.)
```

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Rice-Yield-Analysis.git
   cd Rice-Yield-Analysis
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run preprocessing:

   ```bash
   python scripts/Data-Preprocessing.py
   ```
4. Run visualization:

   ```bash
   python scripts/Data-Visualization.py
   ```
5. Train and run prediction model:

   ```bash
   python scripts/PredictionModel.py
   ```

---

## 📊 Example Outputs

* Crop yield trend visualizations
* Protein deficiency severity predictions
* Recommended fertilizers and rice varieties

---

---

## 📜 License

This project is licensed under the MIT License.

---

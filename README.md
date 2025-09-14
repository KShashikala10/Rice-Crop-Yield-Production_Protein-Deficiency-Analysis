
---

# 🌾 Rice Crop Yield Prediction & Protein Deficiency Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-pandas-green.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Library-seaborn-lightblue.svg)](https://seaborn.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/ML-scikit--learn-orange.svg)](https://scikit-learn.org/stable/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project leverages **Python, Pandas, Seaborn, and Machine Learning** to analyze rice crop yield, soil conditions, and protein deficiency severity. By combining data preprocessing, predictive modeling, and visualization, it provides actionable insights and recommendations to improve rice production and address nutritional deficiencies.

---

## 📌 Features

* 🔄 **Data Preprocessing** – Cleans, structures, and prepares agricultural data for analysis.
* 📊 **Exploratory Data Analysis (EDA)** – Visualizes yield patterns, soil characteristics, and environmental factors.
* 🤖 **Machine Learning Models** – Random Forest predicts yield, protein deficiency severity, and recommends rice varieties.
* 📉 **Visualization Tools** – Generates bar charts, scatter plots, heatmaps, and pie charts.
* 📝 **User Input & Prediction** – Interactive model accepts soil/environmental conditions and predicts yield.
* 💡 **Recommendation System** – Suggests fertilizers, soil management techniques, and rice varieties.

---

## ⚙️ Tech Stack

* **Language**: Python 3.x
* **Libraries**:

  * `pandas` – Data preprocessing
  * `seaborn` / `matplotlib` – Data visualization
  * `scikit-learn` – Machine Learning

---

## 📂 Project Structure

```bash
Rice-Yield-Analysis/
│── rice_yield_prediction.csv   # Dataset
│── images/                              # Saved visualizations
│   ├── yield_comparison.png
│   ├── correlation_heatmap.png
│   ├── soil_type_distribution.png
│   ├── Protein_Deficiency_Severity_Distribution.png
│   ├── average_yield_by_region.png
│   └── rainfall_vs_yield.png
│── Data-Collection.py                   # Collects agricultural data
│── Data-Preprocessing.py                # Cleans & preprocesses dataset
│── Data-Visualization.py                # Generates visualizations
│── PredictionModel.py                   # Random Forest prediction model
│── README.md                            # Documentation
```



---

## 🚀 Usage Example

**Sample Input**

```
Enter the following details to predict yield, protein deficiency, and rice variety:
Temperature (°C): 29
Rainfall (mm/month): 180
Soil pH: 6.5
Nitrogen Fertilizer Used (kg/ha): 50
```

**Sample Output**

```
Predicted Yield (kg/ha): 4614.84
Predicted Protein Deficiency Severity: Moderate
Suggested Rice Variety: Pusa Basmati

Recommendations to Reduce Protein Deficiency:
- Use high-protein rice varieties such as Swarna Sub1 or Dhan 44.
- Increase organic matter in soil using compost or vermicompost.
- Apply micronutrient fertilizers like Zinc Sulfate or Boron (Borax).
```

---

## 📊 Example Visualizations

### Yield Comparison Across Rice Varieties
### Correlation Heatmap
### Soil Type Distribution
### Rainfall vs Yield with Protein Deficiency Severity

---

## 📜 License

This project is licensed under the MIT License.

---


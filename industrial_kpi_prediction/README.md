
# Industrial Quality KPI Prediction (Machine Learning)

This project demonstrates a complete Machine Learning workflow for predicting Quality KPIs in an industrial manufacturing environment.

## 📊 Dataset
Synthetic manufacturing dataset (600 days), including:
- Production Volume
- Downtime Minutes
- Scrap Rate
- Line Speed
- Cycle Time
- Operator Load
- **Quality KPI (target)**

## 🔧 Workflow
1. EDA (correlation heatmap, distributions)
2. Feature engineering & preprocessing
3. Random Forest model training
4. Model evaluation (MAE, R²)
5. Feature importance analysis
6. Actual vs Predicted visualization

## 📈 Results
- **MAE ≈ 1.29**
- **R² ≈ 0.80**
- Scrap Rate and Downtime are key drivers of KPI changes
- Line Speed positively affects KPI performance

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP (model interpretability)

## 📁 Files
| File | Description |
|------|------------|
| industrial_kpi_data.csv | Synthetic dataset |
| industrial_kpi_prediction.ipynb | Full ML pipeline |
| industrial_kpi_project_plots.pdf | Visualizations |

## 🚀 Summary
This project simulates a real-world manufacturing analytics use case, showing how Machine Learning can support quality prediction and operational decision-making.

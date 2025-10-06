# Life Expectancy Prediction

This project uses machine learning techniques to predict life expectancy based on global health and socio-economic data from 193 countries (2000–2015). It explores key predictors such as HIV/AIDS prevalence, adult mortality, immunization rates, and income composition to gain insights into factors influencing life expectancy.

## Project Highlights

- Comprehensive data cleaning and preprocessing, including imputation and outlier treatment.
- Exploratory data analysis with visualizations and correlation studies.
- Multiple regression models built and evaluated: Ridge, Lasso, Random Forest, Gradient Boosting, XGBoost, SVR.
- Feature scaling and importance analysis.
- Model performance assessed using \(R^2\), RMSE, and MAPE metrics.
- Strong predictive accuracy from tree-based ensemble models.
- Insights relevant for guiding public health policies.

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook for interactive analysis
- XGBoost for gradient-boosted trees

## Usage

The Jupyter notebook (`Life_expectancy_Regression.ipynb`) walks through the entire workflow from data preprocessing to model evaluation. To run the project:

1. Clone the repository.
2. Create a virtual environment (recommended) and activate it.
3. Open and run the notebook

## Data Source

The dataset used is sourced from the World Health Organization (WHO), covering multiple health indicators across countries and years.

## File Structure

- `data/` — raw dataset
- `notebooks/` — `Life_expectancy_Regression.ipynb`
- `README.md` — project overview (this file)

## Results

- Tree-based ensemble models (Random Forest, XGBoost) produced the best predictive performance on test data.
- Top predictors included HIV/AIDS prevalence, Adult Mortality, and Income Composition of Resources.

## License

This project is open source.

## Contact

For questions or collaboration, contact: Sourav (msourav222@gmail.com).


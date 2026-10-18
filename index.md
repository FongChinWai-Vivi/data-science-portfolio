

# Fong Chin Wai (Vivi)

MSc Data Science, University of Macau — Student ID: mc653748

Data science enthusiast working with Python to turn raw data into clean,
reproducible analyses and clear visualizations.

## Technical Skills

- **Programming:** Python, SQL
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (linear & Ridge regression, cross-validation, model evaluation)
- **Tools & Workflow:** Jupyter Notebook, Git, GitHub, GitHub Pages

## Projects

### 1. Regression Analysis for Pricing Prediction — *completed*

[data-science-project repository](https://github.com/FongChinWai-Vivi/data-science-project)

**Research question:** How accurately can the market price of a product or property
(used cars, laptops, and houses) be predicted from its features using regression models?

Using pandas, scikit-learn and matplotlib, I built and refined linear regression models
across six modules: data acquisition, wrangling, EDA, linear regression, and finally
cross-validation with Ridge regression and grid-search tuning. The analysis shows that
**engine size and horsepower dominate automobile price, while square footage dominates
house price**; Ridge regression with a tuned alpha clearly improves test-set R² compared
with plain polynomial regression.

![Engine size vs price](assets/regression/images/m03_scatter_engine_size_vs_price.png)

*Engine size shows a clear positive relationship with automobile price.*

![Model comparison R2 and MSE](assets/regression/images/m04_model_comparison_r2_mse.png)

*Cross-validation and Ridge regression improve test performance.*

![Grid search alpha tuning](assets/regression/images/m05_gridsearch_alpha_tuning.png)

*Grid search identifies the best ridge regularization strength.*

*Data exploration steps from the assignment:*

![Numeric columns description](assets/assignment1/images/a1_describe_numeric_columns.png)

![Data types and describe](assets/assignment1/images/a1_lab02_data_types_and_describe.png)

![Missing values handled](assets/assignment1/images/a1_replace_question_marks_with_nan.png)

*Inspecting data types and handling `?` missing values with `NaN` before modeling.*

**Notebooks:** [Download from the project repository](https://github.com/FongChinWai-Vivi/data-science-project/tree/main/notebooks)

**Status:** completed

---

### 2. Is Macau's Transport Keeping Up With Its Visitors? — *completed*

[Preliminary project repository](https://github.com/FongChinWai-Vivi/CISC7204-MC653748-2026GitHub)

**Research question:** Does Macau's public transport network supply match the demand
created by its rapidly growing visitor arrivals, especially during peak events?

This preliminary study combines visitor arrival data with bus route and stop data to
compare transport supply and demand across districts and time periods.

![Bus stop supply and demand](assets/project/images/fig1_supply_demand_match.png)

*586 bus stops mapped by service coverage: the Macau Peninsula has the densest network,
followed by Cotai.*

![District demand vs supply](assets/project/images/fig2_district_event_shuttle.png)

*Visitor demand is concentrated in the Macau Peninsula while Cotai's supply is relatively
more sufficient — Coloane shows the highest supply–demand ratio (2.99).*

**Status:** completed

---

*Hosted with GitHub Pages. Built for CISC7204 Practice 9 (Build Your Data Science Portfolio).*


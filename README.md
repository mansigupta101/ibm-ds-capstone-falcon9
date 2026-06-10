# Falcon 9 First-Stage Landing Outcome Predictor
 
Python scripts for predicting Falcon 9 first-stage landing outcomes using machine learning - IBM Applied Data Science Capstone Project.
 
---
 
## Project Overview
 
SpaceX advertises Falcon 9 rocket launches at a significantly lower cost than competitors, largely because the first stage can be recovered and reused. Predicting whether the first stage will successfully land allows us to estimate launch cost, which is valuable for companies competing against SpaceX.
 
This project collects launch data, performs exploratory analysis, and builds classification models to predict landing success.
 
---
 
## Objectives
 
- Collect and wrangle Falcon 9 launch data via the SpaceX REST API and web scraping
- Perform exploratory data analysis (EDA) using SQL and visualizations
- Generate interactive maps and dashboards to access outcomes at each site
- Build and evaluate machine learning classification models
- Identify the best-performing model for predicting landing outcomes
---
 
## Repository Structure
 
```
├── notebooks/              # Jupyter notebooks (data collection & wrangling, EDA, visualization, modeling)
├── workflow/               # Flowcharts
├── results_images/         # Result images
├── README.md
└── requirements.txt
```
 
---
 
## Methods
 
- **Data Collection** — SpaceX REST API, BeautifulSoup web scraping
- **Data Wrangling** — Pandas, one-hot encoding, feature engineering
- **EDA** — SQL queries, Matplotlib, Seaborn, Folium maps, Plotly Dash dashboard
- **Machine Learning** — Logistic Regression, Decision Tree, SVM, KNN (scikit-learn)
- **Model Evaluation** — Accuracy, confusion matrix, GridSearchCV tuning
---
 
## Requirements
 
```bash
pip install -r requirements.txt
```
 
Key dependencies: `pandas`, `numpy`, `beautifulsoup4`, `requests`, `matplotlib`, `seaborn`, `folium`, `plotly`, `dash`, `scikit-learn`
 
---
 
## Usage
 
Run the notebooks in order:
 
1. `01_data_collection_api.ipynb` — Fetch data from SpaceX REST APIs
2. `02_data_collection_scraping.ipynb` — Web Scrape Wikipedia table for falcon 9 launch data
3. `03_data_wrangling.ipynb` — Clean and prepare the dataset
4. `04_eda_sql.ipynb` — Exploratory data analysis (EDA) with SQL
5. `05_eda_visualization.ipynb` — EDA with visualization
6. `06_launch_site_map.ipynb` — Interactive map with Folium
7. `07_dashboard.ipynb` — Plotly Dash interactive dashboard
8. `08_predictive_analysis.ipynb` — ML model training, tuning and evaluation
---
 
## Results
 
The best-performing model achieved **X% accuracy** on the test set. >>>>>......update this also: Logistics Regression, Decision Tree and SVM models showed strong performance after hyperparameter tuning with GridSearchCV.
 
> INCOMPLETE: add results.
 
---
 
## Certificate
 
[IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) — Applied Data Science Capstone
 
---
 
# License
 
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

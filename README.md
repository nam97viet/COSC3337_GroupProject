# Comprehensive Analysis and Predictive Modeling of Global COVID-19 Trends

## 📚 Course Information
- **Course**: COSC 3337 - Data Science I
- **Section**: 15902
- **Instructor**: Jingchao Ni
- **Semester**: Spring 2025

## 👨‍💻 Group Members
- **Chongyi Wang** - 2244409  
- **Nathan Tran** - 2049679  
- **Victor Ha** - 2018028  

## 📂 Included Files
- [`owid_covid_data_us_subset.csv`](owid_covid_data_us_subset.csv) — COVID-19 dataset (United States subset) from Our World in Data.
- [`main.ipynb`](main.ipynb) — Jupyter Notebook containing all code for:
  - Data preprocessing
  - Data visualization
  - Clustering (KMeans, DBSCAN)
  - Classification (Decision Tree, KNN, SVM)
  - LSTM model for time-series forecasting
- [`Final_Report.pdf`](Final_Report.pdf) — Full project report that analyzes the COVID-19 dataset and summarizes results and findings.

## 📈 Dataset Description
- **Source**: Our World in Data (OWID)
- **Content**: Daily COVID-19 statistics including:
  - Total cases
  - New cases
  - Total deaths
  - Hospitalization and ICU rates
  - Other pandemic-related indicators for the United States

## 🛠 Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
- `statsmodels`
- `tensorflow` (Keras API)

## 🚀 How to Run

1. **Install Required Libraries**

   Run the following command:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn scipy statsmodels tensorflow
   ```

2. **Open and Execute the Notebook**
   - Launch Jupyter Notebook or JupyterLab.
   - Open `main.ipynb`.
   - Ensure that `owid_covid_data_us_subset.csv` is in the same directory.
   - Execute all cells sequentially to:
     - Preprocess the data
     - Generate data visualizations
     - Apply clustering algorithms
     - Train and evaluate classification models
     - Train and forecast with LSTM models

3. **Review the Final Report**
   - Open `Final_Report.pdf` for a detailed analysis and summary of the project findings and results.

## 📊 Expected Outputs
- Graphs and plots showing COVID-19 case trends
- Clustering visualizations (KMeans, DBSCAN)
- Classification performance metrics (accuracy, precision, recall)
- Time-series forecasting plots (LSTM prediction curves)
- Comprehensive analysis documented in the Final Report

## 📝 Notes
- Figures generated from `main.ipynb` match those shown in `Final_Report.pdf`.
- Feature scaling (`StandardScaler`, `MinMaxScaler`) is applied where needed.
- Random seeds are set where applicable to ensure reproducibility.

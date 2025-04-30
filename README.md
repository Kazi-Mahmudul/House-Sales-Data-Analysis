# 🏠 House Sales Data Analysis (King County, USA)

This project is an end-to-end exploratory data analysis (EDA) of the **House Sales in King County, USA** dataset using Python and Jupyter Notebook. The goal is to understand the key factors influencing house prices and apply data cleaning, visualization, and basic statistical techniques.

## 🔍 Project Tasks

1. **Dataset Setup**
   - Downloaded and loaded the dataset using Pandas.
   - Displayed the first 10 rows for inspection.

2. **Initial Exploration**
   - Reviewed column names, data types, and null value counts.
   - Identified and removed duplicate entries.
   - Converted date columns into proper datetime formats.

3. **Data Cleaning**
   - Handled missing values column-wise with proper justification.
   - Created derived features such as:
     - `total_area` = `sqft_living` + `sqft_lot`
     - `property_age`, `price_per_sqft`, etc.
   - Identified and handled outliers using statistical methods.

4. **Exploratory Data Analysis**
   - Summary statistics for all numeric columns.
   - Visualized the distribution of house prices.
   - Explored relationships between price and features like area, bedrooms, and location.
   - Created visualizations:
     - Time trends in prices
     - Correlation heatmaps
     - Additional creative and insightful plots

5. **Basic Statistical Analysis**
   - Calculated mean, median, and mode for price and total area.
   - Performed t-tests to analyze significance of differences in price based on features.
   - Interpreted results and documented findings.

6. **Documentation**
   - Explained the rationale behind each step taken.
   - Clearly documented findings from visual and statistical analyses.

## 📁 Dataset

- **Source:** [Kaggle - House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)
- **Rows:** 21,613
- **Columns:** 21 features including prices, bedrooms, area, year built, and more

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook / IPython
- Pandas
- Matplotlib / Seaborn
- SciPy (for statistical testing)

---

## 📸 Visualizations

### 📊 Distribution of House Prices
![Distribution](https://i.postimg.cc/Wzhc8Ym6/distribution-hp.png)

### Average Price by Total Area
![avg_hp](https://i.postimg.cc/904sZRVL/avg-price-by-total-area.png)

### 🔥 Correlation Heatmap
![Heatmap](https://i.postimg.cc/QdgwQrGZ/correlation-heatmap.png)

### 📈 House Price Trends Over Time
![Time Trend](https://i.postimg.cc/N0gVbPB9/hp-trend.png)

### 🧮 Correlation with House Price
![Correlation_hp](https://i.postimg.cc/fLPrzzXm/correlation-hp.png)

---

## Author
Kazi Mahmudul Hasan 
- GitHub: [Kazi-Mahmudul](https://github.com/Kazi-Mahmudul)
- LinkedIn: [Kazi-Mahmudul-Hasan](www.linkedin.com/in/kazi-mahmudul-hasan)



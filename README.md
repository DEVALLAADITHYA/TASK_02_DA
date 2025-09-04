# TASK_02_DA
Exploratory Data Analysis (EDA) – Business Insights from Dataset

📌 Objective

The goal of this task was to perform Exploratory Data Analysis (EDA) on a dataset to uncover meaningful business insights using visualizations and statistical summaries.
The analysis helps to:

Understand variable distributions

Detect missing values and anomalies

Explore correlations and relationships between variables

Identify outliers and skewness

Prepare the dataset for further modeling

🛠️ Tools Used

Python (Pandas, NumPy)

Visualization: Seaborn, Matplotlib

Platform: Google Colab / Jupyter Notebook

🔹 Dataset Description

(Example: Titanic / Supermarket Sales / Retail Sales — replace with your actual dataset)

Typical columns explored:

Categorical Features: Gender, Product Category, Payment Method, Survival Status, etc.

Numerical Features: Age, Income, Quantity, Spending Score, etc.

🔹 EDA Steps
1️⃣ Data Inspection

Loaded dataset using Pandas (read_csv, read_excel)

Checked shape, data types, and info using .shape, .info()

Generated summary statistics with .describe()

Identified missing values with .isnull().sum()

2️⃣ Missing Values Analysis

Visualized missing data using Seaborn heatmap

Calculated % of missing values

3️⃣ Univariate Analysis

Histograms & KDE plots → Numerical feature distributions

Boxplots → Outlier detection

Countplots → Frequency distribution of categorical variables

4️⃣ Bivariate Analysis

Correlation Heatmap → Relationship between numerical variables

Pairplot (sampled data) → Variable interactions

Groupby analysis → Category-level patterns

5️⃣ Outliers & Skewness

Checked skewness using .skew()

Applied log transformation for highly skewed variables

Visualized outliers with boxplots

6️⃣ Data Export

Saved processed dataset as processed_dataset.csv

Exported analysis report as PDF

🔹 Deliverables

EDA Notebook → EDA_Notebook.ipynb

Cleaned Dataset → processed_dataset.csv

PDF Report of Findings → report.pdf

📊 Key Insights (Example)

(Replace with findings from your dataset)

Younger customers had higher spending scores compared to older ones

Strong positive correlation between Annual Income and Spending Score

Certain product categories showed seasonal spikes in sales

Missing values concentrated in demographic-related fields


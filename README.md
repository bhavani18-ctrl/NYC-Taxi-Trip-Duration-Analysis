# NYC-Taxi-Trip-Duration-Analysis
This project analyzes the New York City Taxi Trip Duration dataset to understand the key factors that influence how long a taxi trip takes. Using a randomly sampled subset of 100,000 records, the project performs data cleaning, exploratory data analysis, feature engineering, regression modeling, and geographic visualization.
📌 Project Tasks
1. Data Preprocessing

Loaded and sampled the dataset (100,000 rows using a fixed random seed).

Checked data types, summary statistics, and missing values.

Cleaned inaccurate records and handled categorical features.

Normalized numerical features and removed outliers.

2. Relationship Discovery

Computed correlations between features.

Applied basic regression to identify predictors of trip duration.

Created new features such as trip distance, hour of day, and weekday.

3. Data Visualization

Plotted distributions of key features (duration, distance, passenger count).

Visualized relationships between distance, time, and duration.

Mapped pickup and drop-off coordinates.

4. Algorithm & Data Structure Efficiency

Linked List / Balanced Tree recommended for maintaining trip duration in sorted order with frequent inserts.

Hash Table recommended for fast lookup using passenger phone numbers.

5. Final Insights

Factors affecting trip duration:

Trip distance

Time of day

Location congestion

Weekday vs weekend patterns

Recommendations include dynamic routing, traffic-aware scheduling, and improved resource allocation.

📂 How to Use

Download the dataset from Kaggle:
https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data

Place train.csv in a /data folder.

Run the Jupyter Notebook to reproduce analysis.

🛠️ Tools Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

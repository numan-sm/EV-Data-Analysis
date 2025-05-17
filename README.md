🚗🔋 Electric Vehicle Data Analysis Project
- Project Overview -
- 
This project analyzes Electric Vehicle (EV) data using Python libraries like Pandas, Seaborn, Matplotlib, and Scipy. The goal is to uncover insights, detect unusual data points (outliers), conduct hypothesis testing, and make actionable recommendations for EV buyers and manufacturers.

📂 Files Included-

File Name	Description

Project.ipynb	Jupyter Notebook with full Python code

Project.pdf	PDF export of the notebook

FEV-data-Excel.xlsx	Dataset containing EV data

Python Final Project PDF.docx.pdf	Problem statement and project guidelines

🧰 Libraries Used

pandas

numpy

matplotlib

seaborn

scipy

✅ Tasks Covered

✅ Task 1: EV Filtering & Grouping

Filter EVs within 350,000 PLN budget with minimum 400 km range.

Group these EVs by manufacturer.

Calculate average battery capacity per manufacturer.

✅ Task 2: Outlier Detection

Analyze energy consumption (kWh/100 km).

Identify unusually high/low consumption using IQR (Interquartile Range).

✅ Task 3: Battery Capacity vs Range Analysis

Scatter plot to visualize relationship.

Key insights about battery size and driving range.

✅ Task 4: EV Recommendation System

Built a Python class to recommend top 3 EVs based on user’s:

Budget

Minimum required range

Minimum required battery capacity

✅ Task 5: Hypothesis Testing

Compared average engine power of Tesla vs Audi using:

Two-sample t-test (ttest_ind from scipy.stats).

Provided insights and recommendations based on test results.

📊 Insights from Analysis

🔋 Bigger Battery = Longer Range (Strong Positive Correlation)

⚠️ However, some EVs with large batteries had lower than expected range — indicating inefficiency, higher weight, or poor aerodynamics.


📊 Tesla vs Audi - Engine Power

No statistically significant difference between their average engine power.

Customers should focus more on range, charging speed, and interior quality rather than power alone.

⚡ Outliers in Energy Consumption


Some EVs consumed much more energy than average — these are potential red flags for buyers.

💡 Recommendations

📣 For Manufacturers

Focus marketing on range, charging speed, and efficiency rather than just power.

Work on improving battery efficiency and vehicle aerodynamics.

📣 For Customers

Long-distance drivers should focus on high battery capacity + efficient design.

City commuters can save money by choosing smaller, cost-effective EVs.

Look for independent reviews that test real-world range.


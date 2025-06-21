# 🚢 Titanic Dataset Analysis and Visualization
This project involves a complete exploratory data analysis (EDA) on the Titanic dataset using Python. It covers missing value treatment using machine learning, feature understanding, and data visualization to uncover insights.

📁 Dataset
The dataset used is the Titanic dataset, loaded directly from Seaborn's inbuilt datasets. It contains information about the passengers aboard the Titanic, including:

• Passenger demographics (age, gender, class, etc.)

• Survival status

• Fare paid

• Embarkation location

• And more

🔧 Technologies Used
• Python

• Pandas, NumPy – Data manipulation

• Seaborn, Matplotlib – Data visualization

• Scikit-learn – Imputation using machine learning

🧠 Process Description
1. Dataset Loading
• Titanic dataset is loaded using sns.load_dataset('titanic').

• Initial rows and dataset shape are printed.

• Column names and data types are explored.

2. Missing Value Analysis
• Total and percentage of missing values per column are calculated.

• A heatmap is used to visually identify missing data patterns.

3. Handling Missing Values
• Numerical columns: Missing values are filled using Iterative Imputer with a Random Forest Regressor, which estimates values based on patterns in other features.

• Categorical columns: Missing values are filled using the mode (most frequent value).

4. Data Summary
• A full statistical summary of all columns is displayed.

• Data types and null counts are inspected to ensure completeness after imputation.

5. Visualization Tools
• Heatmap of missing values: Before imputation

• (Other potential visualizations such as survival counts, fare distributions, and class-based insights can be added in future versions.)

📈 Key Insights (Potential for Expansion)
• Analyze survival based on gender and class.

• Examine fare and age distributions.

• Detect bias and imbalance in data distributions.

• Build a predictive model in future steps.

▶️ How to Run
1. Clone this repository:
   
git clone https://github.com/yourusername/titanic-data-analysis.git
cd titanic-data-analysis

2. Open assignment4.ipynb in Jupyter Notebook or VS Code.

3. Execute each cell step-by-step.

✅ Future Enhancements
• Visualize survival rate by age, gender, and class.

• Perform feature engineering (e.g., creating family size or title columns).

• Train a logistic regression or random forest classifier.

• Evaluate classification performance metrics (accuracy, precision, recall, F1-score).

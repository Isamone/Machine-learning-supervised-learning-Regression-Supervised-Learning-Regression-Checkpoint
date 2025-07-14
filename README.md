5G Energy Consumption Prediction Project
🎯 Objective
This project aims to build and train a machine learning model that estimates the energy consumption of 5G base stations, considering:

Engineering configurations

Traffic conditions

Energy-saving strategies

The project is based on the '5G Energy Consumption' dataset provided by the International Telecommunication Union (ITU) in 2023, as part of a global challenge for data scientists.

📋 Project Workflow
1. 📥 Data Handling
Import and Explore Dataset: Load the dataset and examine its structure and contents.

Display General Information: View data types, shape, and basic statistics using .info() and .describe().

Generate Profiling Report: Use pandas-profiling to perform automated exploratory data analysis.

Handle Missing Values: Identify and treat missing or corrupted data entries.

Remove Duplicates: Drop duplicate records to ensure data integrity.

Detect and Treat Outliers: Use statistical techniques or visualizations (box plots, z-score, etc.) to identify outliers.

Encode Categorical Features: Convert categorical variables into numerical format for ML algorithms.

Feature and Target Selection: Choose relevant features and set the target variable (e.g., Energy).

Split Dataset: Divide data into training and test sets using train_test_split().

2. 🤖 Model Building and Evaluation
Algorithm Selection: Choose a suitable regression algorithm (e.g., Linear Regression).

Model Training: Fit the model using the training dataset.

Model Evaluation: Assess the model on the test data using metrics like:

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

🛠️ Tools & Technologies Used
Tool/Library	Purpose
Python	Programming language
VSCode	Code editor
Git & GitHub	Version control & project hosting
Pandas & NumPy	Data handling and numerical ops
Matplotlib & Seaborn	Visualization tools
pandas-profiling	Automated exploratory data analysis
Scikit-learn	Machine learning modeling
Google / YouTube	Research and tutorials


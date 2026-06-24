# Laptop-price-analysis💻

This project explores the factors influencing laptop prices through exploratory data analysis and predictive modeling. The study examines hardware specifications, brand characteristics and display features to understand their impact on pricing and develops a machine learning model for price prediction.

# Objectives
To analyze the factors influencing laptop prices and develop a machine learning model capable of predicting laptop prices based on hardware specifications and product features.
  
# Tech Stack
- Programming Language: Python
- Data Analysis: Pandas, NumPy
- Data Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn, Linear Regression
- Development Environment: Jupyter Notebook

# Data Preprocessing

The dataset was prepared for analysis through the following preprocessing steps:

- Inspected dataset structure and data types.
- Handled missing values in storage related features.
- Converted RAM values from text format to numeric format.
- Encoded categorical variables using one hot encoding.
- Transformed binary features into numerical representations.
- Prepared feature and target datasets for model training.

# Analysis Performed
➜ Brand Distribution Analysis
- Analyzed the distribution of laptop manufacturers across the dataset.

➜ Laptop Type Analysis
- Examined the frequency of different laptop categories.

➜ Operating System Analysis
- Explored the distribution of operating systems among laptops.

➜ Hardware Component Analysis
- Investigated CPU manufacturers, GPU manufacturers, and storage configurations.

➜ Display Feature Analysis
- Analyzed touchscreen availability, Retina Display, IPS Panel, and screen resolution distributions.

# Feature-Wise Price Analysis

• Evaluated how laptop prices vary across:
- Company
- Operating System
- Laptop Type
- CPU Manufacturer
- GPU Manufacturer
- Storage Type
- Touchscreen Availability
- Retina Display
- IPS Panel
- Screen Resolution
  
# Machine Learning Model
- Developed a Linear Regression model to predict laptop prices based on hardware specifications and laptop features.
  
# Evaluation Metrics
- R² Score: 0.77

# Key Findings

- Brand positioning significantly influences laptop pricing with premium manufacturers commanding higher price points.
- Laptop categories exhibit distinct pricing patterns based on performance and target market segments.
- CPU and GPU configurations play a crucial role in determining laptop prices.
- Premium display features, including Touchscreen, Retina Display and IPS Panels are commonly associated with higher priced devices.
- Storage configurations and screen resolutions contribute notably to price variation.
- The Linear Regression model achieved an R² score of 0.77, demonstrating strong predictive capability.
- Actual versus predicted price comparisons highlighted the model's effectiveness in estimating laptop prices.




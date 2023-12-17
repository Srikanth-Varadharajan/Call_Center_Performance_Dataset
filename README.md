<title># Call_Center_Performance_Dataset<title/>
<body>Overview<br/>
<p>This repository contains Python code for analyzing the Call Center Performance Dataset. The dataset includes information about incoming calls, abandonment rates, service levels, and other relevant metrics for a call center.<br/>

Code Explanation<br/>
1. Data Loading and Exploration<br/>
The script starts by loading the dataset from a CSV file into a Pandas DataFrame. Basic exploration is performed using info(), shape, duplicated().sum(), and describe() to understand the structure and characteristics of the data.<br/>
2. Data Cleaning<br/>
The 'Index' column is dropped from the DataFrame.<br/>
3. Date and Time Conversion<br/>
Date and time columns are converted to datetime format for analysis. Subsequently, these datetime values are converted to decimal format for statistical calculations.<br/>
4. Data Type Conversion<br/>
Percentage columns ('Answer Rate' and 'Service Level (20 Seconds)') are cleaned and converted to float data type.<br/>
5. Data Visualization<br/>
Matplotlib and Seaborn are used to create histograms, scatter plots, and heatmaps for visualizing the distribution and relationships within the dataset.<br/>
6. Linear Regression<br/>
Simple linear regression is performed to analyze the relationship between 'Abandoned Calls' and 'Incoming Calls'. Additionally, multiple linear regression is used to predict 'Abandoned Calls' based on other variables.<br/>
7. Evaluation Metrics<br/>
The R-squared value is calculated for simple linear regression, and the accuracy is computed for multiple linear regression.<br/>
8. Additional Visualizations<br/>
Scatter plots are generated to visualize relationships between various variables. Specific scatter plots highlight the impact of 'Abandoned Calls' on other metrics.<br/>
9. Histogram Plot<br/>
A histogram plot is created to visualize the distribution of 'Service Level (20 Seconds)'.<br/>
Usage<br/>
Ensure you have Python and the required libraries installed (Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn).<br/>
Clone the repository.<br/>
Run the script in a Jupyter Notebook or any Python environment.<br/>
Contributing<br/>
Feel free to contribute by opening issues or submitting pull requests.<br/></p>

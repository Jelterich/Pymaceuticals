# Pymaceuticals Inc. - Tumor Volume and Mouse Weight Analysis
Overview
What good is data without a good plot to tell the story?

In this assignment, you'll apply what you've learned about Matplotlib to a real-world situation and dataset to analyze tumor development over time in mice treated with various drug regimens.

Background
You've just joined Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. Recently, the company started screening potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer.

As a senior data analyst, you’ve been given access to data from a recent animal study in which 249 mice, identified with SCC tumors, were treated with various drug regimens. Tumor development was observed over a period of 45 days, and the purpose of this study was to compare Pymaceuticals' drug of interest, Capomulin, with other treatment regimens.

The executive team has tasked you with generating all tables and figures required for the technical report and providing a top-level summary of the study results.

Files
To get started, you'll need to download the necessary files:

mouse_metadata.csv: Contains metadata for the mice used in the study.
study_results.csv: Contains the results of the study, including tumor volumes and time points.
Tasks
This analysis is broken down into the following tasks:

Prepare the Data

Merge the mouse_metadata and study_results DataFrames into a single DataFrame.
Display the number of unique mouse IDs, remove duplicates, and ensure the data is clean for analysis.
Generate Summary Statistics

Create a summary table that provides the mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.
Create Bar Charts and Pie Charts

Generate two bar charts to show the total number of rows (Mouse ID/Timepoints) for each drug regimen using both Pandas and Matplotlib.
Generate two pie charts showing the distribution of male versus female mice, using both Pandas and Matplotlib.
Calculate Quartiles, Find Outliers, and Create a Box Plot

Calculate quartiles and interquartile ranges for the four most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
Identify any potential outliers and generate a box plot to visualize the distribution of tumor volumes for the four regimens.
Create a Line Plot and a Scatter Plot

Generate a line plot to show the tumor volume over time for a single mouse treated with Capomulin.
Create a scatter plot comparing mouse weight versus average tumor volume for all mice in the Capomulin treatment group.
Calculate Correlation and Regression

Calculate the correlation coefficient and perform a linear regression analysis between mouse weight and average tumor volume for the Capomulin regimen.
Plot the regression line on the scatter plot to visualize the relationship.
Key Features
1. Prepare the Data
The data is cleaned to ensure no duplicate time points exist for any mouse.
A merged DataFrame is created to include both tumor volumes and mouse metadata.
2. Generate Summary Statistics
For each drug regimen, we calculate the mean, median, variance, standard deviation, and SEM of tumor volume to get a clear summary of the data.
3. Create Bar Charts and Pie Charts
Bar Charts: Two bar charts (using Pandas and Matplotlib) that display the number of timepoints observed for each treatment regimen.
Pie Charts: Two pie charts (using Pandas and Matplotlib) showing the distribution of male and female mice in the study.
4. Calculate Quartiles and Outliers
We calculate quartiles and IQR for Capomulin, Ramicane, Infubinol, and Ceftamin.
Outliers: Any tumor volume outside of the IQR bounds is considered a potential outlier.
Box Plot: A combined box plot shows the tumor volume distribution for each regimen, with potential outliers highlighted.
5. Create Line and Scatter Plots
Line Plot: Visualizes tumor volume over time for a single mouse treated with Capomulin.
Scatter Plot: Shows the relationship between mouse weight and average tumor volume for the Capomulin regimen.
6. Calculate Correlation and Regression
The correlation coefficient between mouse weight and average tumor volume is calculated to assess the strength of the relationship.
A linear regression model is plotted on top of the scatter plot to visualize the trend.
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/pymaceuticals-analysis.git
Install the required Python libraries by running:

bash
Copy code
pip install -r requirements.txt
Run the analysis:

bash
Copy code
python analysis.py
Data Visualization with Matplotlib
We utilized Matplotlib extensively throughout the analysis. The following resources are highly recommended to understand various plotting techniques used in the project:

Matplotlib Documentation: Provides detailed guides and examples on how to use Matplotlib for creating various types of plots.
W3Schools Matplotlib Tutorial: A beginner-friendly introduction to Matplotlib and its key functionalities.
Summary of Results
Capomulin: The Capomulin regimen showed significant effectiveness in reducing tumor volumes over time, as visualized in both line and scatter plots.
Correlation: There is a strong positive correlation between mouse weight and tumor volume, with an R-squared value showing a clear linear relationship between the two variables.
Quartiles and Outliers: Quartile analysis revealed some outliers, which were highlighted in the box plots.
Acknowledgments
Matplotlib Official Documentation
W3Schools - Matplotlib
This analysis uses data visualization to help tell the story behind the effectiveness of Pymaceuticals' drug regimens. With this data, decisions can be made regarding the potential of Capomulin as a treatment option.

License
This project is licensed under the MIT License - see the LICENSE file for details.


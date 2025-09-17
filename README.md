Iris Dataset Analysis
Project Overview
This project analyzes the famous Iris dataset using Python's data analysis and visualization libraries. The assignment demonstrates skills in data loading, exploration, analysis, and visualization.

Dataset Information
The Iris dataset contains measurements of 150 iris flowers from three different species:

Setosa

Versicolor

Virginica

For each flower, four features are measured:

Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Project Structure
text
iris-analysis/
├── Iris_Dataset_Analysis.ipynb  # Main Jupyter notebook
├── requirements.txt              # Python dependencies
├── iris_visualizations.png       # Generated visualizations
└── README.md                    # This file
Requirements
To run this project, you need the following Python libraries:

Python 3.6+

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter

Installation
Clone or download this project

Install the required packages:

bash
pip install -r requirements.txt
Or manually install:

bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
How to Run the Analysis
Open a terminal/command prompt

Navigate to the project directory

Start Jupyter Notebook:

bash
jupyter notebook
In the web interface, click on Iris_Dataset_Analysis.ipynb

Run the cells sequentially using Cell > Run All or run each cell individually with Shift + Enter

Assignment Tasks Completed
Task 1: Load and Explore the Dataset
Loaded the Iris dataset using scikit-learn

Displayed the first few rows of the dataset

Explored the dataset structure and data types

Checked for missing values (none found)

Task 2: Basic Data Analysis
Computed basic statistics for numerical columns

Grouped data by species and calculated mean values

Identified patterns and differences between species

Task 3: Data Visualization
Created four different visualizations:

Line chart showing measurement trends across species

Bar chart comparing average petal length per species

Histogram showing distribution of sepal length

Scatter plot visualizing relationship between sepal length and petal length

Key Findings
Species Differences:

Setosa flowers have the smallest measurements

Virginica flowers have the largest measurements

Versicolor flowers are intermediate in size

Measurement Patterns:

Strong positive correlation between petal length and petal width

Sepal length and petal length are also positively correlated

Setosa is clearly distinguishable from other species based on petal measurements

Data Quality:

No missing values in the dataset

All measurements are numerical with appropriate data types

Files Included
Iris_Dataset_Analysis.ipynb: Main Jupyter notebook with complete analysis

iris_visualizations.png: Combined visualization of all plots

requirements.txt: List of Python dependencies

README.md: This documentation file

Additional Notes
The project uses try-except blocks for error handling when loading data

Visualizations are customized with titles, labels, and legends for clarity

The analysis follows best practices for data exploration and visualization

# Health Data Analysis using Python

This repository contains the code and data for analyzing health data using Python. The analysis aims to determine the correlation between education level, waist circumference, and blood glucose in a given population. The analysis utilizes regression analysis techniques to assess the relationship between these variables.

## Conclusions

Using linear regression analysis, it was found that education level and weight circumference are linearly correlated with one's blood glucose level. However due to the small regression coeffecient, the model cannot has no predictive capability. Furthermore, despite the uncorrelated p-value being less than the alpha value (<0.5) the F-value from both education level(1.29) and wasit circumference(23.64) smaller than the critical F-value(254), the correlation found in this study is likely due to random chance therefore it's not statistically significant. The conclusion of the study insignificance can also be confirmed using the partial eta squared since the value is very small.
 
## Dataset
The dataset used for this analysis is provided in the data directory. The dataset should be in a comma-separated values (CSV) format, where each row represents an individual's health information, including education level, waist circumference, and blood glucose. The dataset should have appropriate headers for each column. The health data was downloaded from [CDC](https://wwwn.cdc.gov/Nchs/Nhanes/)

## Dependencies
The following Python libraries are required to run the analysis:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- pingouin

## Usage

Clone this repository to your local machine or download the ZIP file.
Ensure that the required dependencies are installed (see the Dependencies section).
Place your health data file (in CSV format) in the data directory.
Open the Jupyter Notebook health_data_analysis.ipynb.
Run the notebook cell by cell to execute the analysis steps.
Analysis Steps
The health_data_analysis.ipynb notebook consists of the following main steps:

Loading the dataset: The notebook reads the health data from the CSV file and creates a Pandas DataFrame for further analysis.

Data preprocessing: This step involves handling missing values, removing outliers, and performing any necessary data transformations.

Exploratory data analysis: The notebook provides visualizations and summary statistics to explore the relationship between education level, waist circumference, and blood glucose.

Regression analysis: The notebook utilizes regression analysis techniques (e.g., linear regression) to quantify the correlation between the variables of interest.

Results and interpretation: The findings and interpretation of the regression analysis are presented in the notebook, highlighting the observed correlation between education level, waist circumference, and blood glucose.

Acknowledgments
We would like to acknowledge the authors and contributors of the libraries used in this analysis, as well as the creators of the dataset used. Their valuable contributions make this analysis possible.





#  Credit Card Approval Analysis Project

## Overview
Developed a logistic regression model to predict customer responses in a marketing campaign, achieving an accuracy of 89%. The model highlighted strengths in identifying non-responders while revealing areas for improvement in predicting responders.

## Libraries Used
The following libraries were utilized in this project:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization.

## Dataset Columns
The dataset contains the following columns:
- **Id**: Unique identifier for each individual.
- **Gender**: Gender of the individual.
- **Own Car**: Indicates whether the individual owns a car.
- **No. of Children**: Number of children the individual has.
- **Income**: Income of the individual.
- **Income Type**: Type of income (e.g., salary, business).
- **Education**: Educational background.
- **Marital Status**: Marital status of the individual.
- **Housing Type**: Type of housing the individual lives in.
- **Date of Birth**: Birthdate of the individual.
- **DAYS_BIRTH**: Age of the individual in days.
- **DAYS_EMPLOYED**: Number of days the individual has been employed.
- **Flag Mobile**: Indicates if the individual has a mobile phone.
- **Flag Work Phone**: Indicates if the individual has a work phone.
- **Flag Phone No.**: Indicates if the individual has a phone number.
- **Flag Mail**: Indicates if the individual has an email address.
- **Occupation**: Occupation of the individual.
- **Cnt Family Members**: Count of family members.
- **Age**: Age of the individual in years.
- **Months Balance**: Balance over the past months.
- **Status**: Target variable indicating the status.
- **Status_Description**: Description of the status.

## Methodology
The methodology involved the following steps:
1. **Data Preprocessing**: Clean the dataset by handling missing values, converting data types, and performing necessary transformations.
2. **Univariate Analysis**: Analyze individual variables to understand their distributions and characteristics.
3. **Bivariate Analysis**: Investigate relationships between pairs of variables to identify any correlations or patterns.

## Univariate Analysis
### Categorical Analysis
- Analyzed categorical features such as `Gender`, `Own Car`, `Income Type`, `Education`, `Marital Status`, `Housing Type`, and `Occupation`.
- Plotted frequency distributions to visualize the prevalence of each category.

### Numerical Analysis
- Examined numerical features like `Income`, `No. of Children`, `DAYS_BIRTH`, `DAYS_EMPLOYED`, `Cnt Family Members`, `Age`, and `Months Balance`.
- Generated descriptive statistics (mean, median, standard deviation) and visualizations (histograms, box plots) to assess distributions.

## Bivariate Analysis
- Explored relationships between variables such as `Income` and `Education`, `Age` and `Marital Status`, and `DAYS_EMPLOYED` and `Income`.
- Used scatter plots and correlation matrices to visualize and quantify relationships among the numerical variables and their impact on the target variable, `Status`.

## Result
- The logistic regression model achieved an accuracy of 89%, effectively identifying non-responders with a precision of 91%. However, the lower precision (63%) for responders indicates a need for further model refinement to enhance predictive performance.

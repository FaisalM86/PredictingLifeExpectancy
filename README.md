# Data Analysis Project - Impact on Life Expectancy

## Overview

This project analyzes the impact of various factors on life expectancy in both developing and developed countries. The dataset used contains information about life expectancy and several key variables, including schooling, BMI, alcohol consumption, immunization rates, and more.

## Table of Contents

- [Project Overview](#overview)
- [Table of Contents](#table-of-contents)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [Impact of Schooling on Life Expectancy](#impact-of-schooling-on-life-expectancy)
  - [Impact of BMI on Life Expectancy](#impact-of-bmi-on-life-expectancy)
  - [Impact of Alcohol on Life Expectancy](#impact-of-alcohol-on-life-expectancy)
  - [Impact of Hepatitis B on Life Expectancy](#impact-of-hepatitis-b-on-life-expectancy)
  - [Impact of Polio on Life Expectancy](#impact-of-polio-on-life-expectancy)
  - [Impact of Diphtheria on Life Expectancy](#impact-of-diphtheria-on-life-expectancy)
  - [Regression Analysis on Immunization](#regression-analysis-on-immunization)
  - [OLS Regression with Additional Variables](#ols-regression-with-additional-variables)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used in this analysis contains the following columns:

- Year
- Life expectancy
- Adult Mortality
- Infant deaths
- Alcohol
- Percentage expenditure
- Hepatitis B
- Measles
- BMI
- Under-five deaths
- ...
- Country
- Status (Developing or Developed)

## Analysis

### Impact of Schooling on Life Expectancy

We investigated the relationship between schooling and life expectancy in both developing and developed countries using scatter plots with regression lines.

### Impact of BMI on Life Expectancy

Similar to schooling, we examined the relationship between BMI and life expectancy in both developing and developed countries using scatter plots with regression lines.

### Impact of Alcohol on Life Expectancy

We analyzed how alcohol consumption affects life expectancy in both types of countries using scatter plots with regression lines.

### Impact of Hepatitis B on Life Expectancy

We explored the effect of Hepatitis B immunization on life expectancy in developing and developed countries.

### Impact of Polio on Life Expectancy

Similarly, we investigated the impact of Polio immunization on life expectancy in both groups.

### Impact of Diphtheria on Life Expectancy

We examined the effect of Diphtheria immunization on life expectancy in both types of countries.

### Regression Analysis on Immunization

We performed a multiple linear regression analysis using variables such as Diphtheria, Polio, and Hepatitis B to predict life expectancy. We also calculated coefficients and metrics like mean squared error and coefficient of determination (R-squared).

### OLS Regression with Additional Variables

We expanded the regression analysis to include additional variables like Alcohol, BMI, and Schooling to predict life expectancy.

## Usage

To use this analysis, you can follow these steps:

1. Clone this repository.
2. Ensure you have the required dependencies installed.
3. Run the Jupyter Notebook or Python script to perform the analysis.

## Dependencies

Make sure to install the following dependencies before running the analysis:

- Python (>= 3.6)
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Statsmodels

You can install most of these dependencies using pip.

```bash
pip install pandas matplotlib seaborn scikit-learn statsmodels
```

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

## Created By
Faisal Mehmood

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to customize this README.md file to include specific details about your project and provide clear instructions for others who might want to use or contribute to it.

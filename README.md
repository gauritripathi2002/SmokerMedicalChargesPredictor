# Linear Regression using Scikit-learn 👾

## Project Overview
This project implements a linear regression model using Python and Scikit-learn to predict medical charges. The dataset used contains information about medical charges based on factors such as age, BMI, smoking status, and region.

### Key Features
- Linear Regression implementation with Scikit-learn
- Data visualization using Plotly, Matplotlib, and Seaborn
- Analysis of factors affecting medical charges
- Estimation and evaluation of charges for smokers

## Installation
Install the required packages using the following command:
!pip install pandas-profiling plotly matplotlib seaborn scikit-learn --quiet

**Note**: Ignore 'llvmlite' error during installation as it does not impact the project functionality.

## Data Acquisition
Data is downloaded using the `urlretrieve` function from `urllib.request`:

## Data Exploration
Load the data into a Pandas DataFrame and perform exploratory data analysis:

## Data Visualization
Visualization is done using Plotly, Matplotlib, and Seaborn:

### Building the Regression Model
The model is built to estimate medical charges for smokers, both manually and using Scikit-learn's LinearRegression.


## Model Evaluation
Evaluate the model using Root Mean Square Error (RMSE) and compare manual estimation with the Scikit-learn model.

## Results and Conclusion
The project concludes with an analysis of the model's performance in predicting medical charges.



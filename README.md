# US Arrests EDA
This is an exploratory data analysis (EDA) titled UsArrests_EDA.ipynb, written in a VSC Jupyter Notebook. The notebook uses the following packages:

## Required Libraries
The following libraries are required to run the code:
- numpy
- pandas
- missingno
- scipy.stats
- mlxtend.preprocessing
- matplotlib.pyplot
- seaborn

## Data Description
The dataset used in this EDA contains statistics on arrests per 100,000 residents for assault, murder, and rape in each of the 50 US States in 1973. Also included is the percentage of the population living in urban areas.

The variables in the dataset are:

Murder: murder arrests per 100,000 residents
Assault: assault arrests per 100,000 residents
Rape: rape arrests per 100,000 residents
UrbanPop: percentage urban population


## Usage
To run the notebook, open the UsArrests_EDA.ipynb file in VSC and run it in a Python environment. The notebook will load the dataset, perform data cleaning and preprocessing, and perform various analyses and visualisations of the data.

The notebook includes the following:

- Data Loading: loads the dataset into a pandas DataFrame
- Data Cleasning: checks for missing values and duplicates, and removes them if necessary
- Data Transformation: scales the data using the min-max scaling method
- Data Gathering (Additional): categorising states by cardinal region
- Data Analysis: performs various statistical analyses on the data, including correlation analysis and hypothesis testing
- Data Visualisation: creates various visualisations of the data using matplotlib and seaborn

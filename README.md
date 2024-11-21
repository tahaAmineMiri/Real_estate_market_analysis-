# Real Estate Market Analysis with Python
This project is part of the Data Analyst Career Track and aims to analyze the real estate market using Python. The analysis involves data cleaning, preprocessing, and various analytical techniques to derive insights from the data.

Table of Contents
- Introduction
- Project Structure
- Data Sources
- Installation
- Usage
- Data Cleaning and Preprocessing
- Analysis
- Results

### Introduction
The goal of this project is to analyze the real estate market by examining various properties and customer data. The analysis includes data cleaning, preprocessing, and visualization to understand trends and patterns in the market.

Project Structure
The project directory is structured as follows:
```
.
├── customers.csv
├── notebook.ipynb
├── properties.csv
├── solution-files-real-estate-market-analysis-with-python/
│   ├── Data Analyst Career Track Project Part 1.ipynb
│   ├── Data Analyst Career Track Project Part 2.ipynb
│   ├── Data Analyst Career Track Project Part 3.ipynb
│   └── Data Analyst Career Track Project.ipynb
└── README.md
```

### Data Sources
The project uses two main data sources:

1. customers.csv: Contains customer information.
2. properties.csv: Contains property information.

### Installation
To run this project, you need to have Python and the following libraries installed:
- `requests`
- `json`
- `pandas`
- `numpy`
- `datetime`
- `matplotlib`
- `seaborn`

You can install the required libraries using pip:

```
pip install requests pandas numpy matplotlib seaborn
```

Usage
To use this project, open the Jupyter notebooks provided in the solution-files-real-estate-market-analysis-with-python directory. Each notebook corresponds to a part of the project:
- ```Data Analyst Career Track Project Part 1.ipynb```
- ```Data Analyst Career Track Project Part 2.ipynb```
- ```Data Analyst Career Track Project Part 3.ipynb```
- ```Data Analyst Career Track Project.ipynb```

Run the cells in the notebooks to perform the analysis.

### Data Cleaning and Preprocessing
The data cleaning and preprocessing steps are documented in the notebooks. Key steps include:

**Reading the Data**: Loading the ```customers.csv``` and properties.csv files using ```pandas.read_csv()```.

**Handling Missing Values**: Replacing placeholders like ```#NUM!``` with ```pd.NA```.

**Data Type Conversion**: Converting columns to appropriate data types (e.g., converting ```price``` to float).

**Standardizing Text**: Converting text to lowercase and stripping unnecessary spaces.

**Date Conversion**: Converting date columns to ```datetime``` objects.

### Analysis
The analysis includes:

**Descriptive Statistics**: Using ```describe()``` to get an overview of the data.

**Data Visualization**: Creating plots using ```matplotlib``` and ```seaborn``` to visualize trends and patterns.

**Merging Data**: Combining the ```customers``` and ```properties``` dataframes using ```pd.merge()```.

### Results
The results of the analysis are documented in the notebooks. Key findings include:

- Trends in property sales over time.
- Customer demographics and their impact on property purchases.
- Price distribution and factors affecting property prices.
# Web-Scraping-COVID-19-Meta-Portal-with-Python

Requests API and Beautiful Soup to scrape real-time COVID statistics from worldometer website and perform data cleaning and visual analysis in Jupyter notebook.

## Data Preparation Notebook

In the first module, web scraping techniques using requests, beautifulsoup packages are utilized to collect and manipulate COVID related data from the worldometer [website](https://www.worldometers.info/coronavirus/)

The notebook has a total of five code blocks.

The first four code blocks provide the following data:

1. Summary Data for ALL Global COVID Cases
2. Summary Data for ACTIVE Global COVID Cases
3. Summary Data for CLOSED Global COVID Cases
4. Tabular Data for COVID Cases by Country

The fifth and final code block provides an interactive interface for exporting each of these four tables

## Data Analysis Notebook

In the second module, data analysis techniques using pandas, numpy, seaborn and statsmodels packages are utilized to collect effective insights from the data and plot necessary graphs. The raw csv data is the same table we collected in Part A of the project taken from the worldometer website regarding COVID cases tabulated by country.

The notebook has a total of twelve code blocks.

1. Importing a CSV file, reading it and counting no. of rows and columns
2. Using the to_numeric method to ensure all numerical columns get passed as numeric
3. Using the describe function to display and analyze basic statistical data on the numerical columns of the imported data
4. Working with a smaller set of imported data - Top 20 countries with most cases
5. Horizontal bar chart to analyze total cases in the top 20 countries
6. Vertical bar chart to analyze total deaths in the top 20 countries with most cases
7. Distribution plot to analyze spread of data for Deaths/1M Population of the 20 countries
8. Using the describe function to display basic statistical data on the numerical columns of the REDUCED dataset
9. Comparing and analyzing mean and standard deviation between population of the Full dataset and the Reduced dataset
10. Using regression scatter plot to check for data independence between tests/million people and the size of the population
11. Finding and analyzing correlations between the variables in the dataset
12. Applying a statistical model to collect useful information about Total Cases and Total Deaths in the full data set

-- Aarif M Jahan -- May 08, 2021

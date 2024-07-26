Global Sustainability Exploration

This project involves data cleaning, preprocessing, and visualization to explore global sustainability trends. The dataset, containing various metrics related to CO2 emissions, energy consumption, and GDP, was analyzed to provide insights into global sustainability.
Overview

    Data Examination:
        Loaded the CSV file and examined the dataset for missing values.
        Plotted missing values to determine their distribution, revealing that missing values were not limited to third-world countries as initially suspected.

    Data Cleaning:
        Checked and filtered data types for future analysis.
        Removed columns with excessive missing values where meaningful imputation wasn't possible.
        Converted the "Density" column to integers and handled zero values to compute a meaningful mean.
        Used the transform function to replace missing values with the mean for each country.
        Dropped columns with no values.

    Enhancements:
        Created a "Continent" column using the pycountry library for improved visualization in Power BI.

    Visualizations:
        Generated a correlation matrix using Spearman correlation to account for non-normally distributed data.
        Renamed columns for better plot readability.

Data cleaning and preparation were performed using Python, and most visualizations were created in Power BI. Raw Python file with comments and Power BI Report are available via the following links:

          https://www.kaggle.com/code/artemkolos/global-sustainability-exploration
          https://shorturl.at/avERM

![Uploading ArcoLinux_2024-07-26_20-58-01.png…]()

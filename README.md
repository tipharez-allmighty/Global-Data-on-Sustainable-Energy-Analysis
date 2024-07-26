I started by loading the CSV file and examining the data. The dataset had numerous missing values, which needed to be addressed. To understand how to handle these missing values, I plotted them and discovered that the missing values were not confined to third-world countries as initially suspected.

I then checked the data types to facilitate future filtering. Columns with excessive missing values were removed, as there was little I could do to fill these gaps meaningfully. For some columns, especially the "Density" column, I converted values to integers and handled zero values to compute a meaningful mean. I used the transform function to replace missing values with the mean for each country.

Some columns had no values at all, making it impossible to replace them with the mean, so I dropped those columns. Despite these challenges, a decent number of samples remained.

Next, I created a "Continent" column using the pycountry library for future visualization in Power BI. Lastly, I plotted the correlation matrix using Spearman correlation because not all data appeared to be normally distributed, and I renamed some columns to improve their appearance on the plot.

Data cleaning and preparation were performed using Python, and most visualizations were created in Power BI. Raw Python file with comments and Power BI Report are available via the following links:

          https://www.kaggle.com/code/artemkolos/global-sustainability-exploration
          https://shorturl.at/avERM

![Uploading ArcoLinux_2024-07-26_20-58-01.png…]()

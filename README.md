This notebook performs an exploratory data analysis of global GDP data from a gdp.csv file.

Data Loading and Initial Exploration
The GDP dataset was loaded into a pandas DataFrame.
Initial checks revealed 11507 entries and 4 columns: 'Country Name', 'Country Code', 'Year', and 'Value' (GDP).
There are 256 unique countries/regions in the dataset.
No missing values were found across any columns.
Descriptive statistics were generated for all columns, showing the range of years (1960-2016) and GDP values.
Data Preparation
A new column named 'GDP' was calculated, representing the year-over-year percentage change in 'Value' (GDP) for each country.
Key Findings and Visualizations
The GDP trend for specific entities like 'Arab World', 'World', and 'India' was analyzed and visualized using line plots.
Countries with the highest average GDP change and highest maximum GDP values were identified.
Individual line plots showing the GDP trend for each of the 256 countries/regions were generated and saved as HTML files in the 'GDP Individual' directory.
Additional plots for each country were generated, setting a consistent y-axis range (0 to 80 trillion) to allow for comparison against the global GDP scale, and saved in the 'GDP Individual WRT World' directory.
Finally, an interactive line plot visualizing the GDP trends of all countries simultaneously, color-coded by country name, was generated and saved as 'CountriesGDP.html'.

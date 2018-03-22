# Austin Housing Data Analsysis

The purpose of this analysis was to look at housing prices in the Austin area spanning the years 2007 - 2016.  The Austin Metropolitan Area is defined differently based on the government agency doing the analysis.  For simplicities sake, only three counties were analyzed: Harris, Williamson, and Travis.  These three counties make up the majority of the Austin area, and it seemed to be a good foundation for analysis

## Data Gathering and Cleaning

All of the data was gathered using the [US Census Website](https://www.census.gov/quickfacts/fact/table/US/PST045217).  The gathered data was all in .csv file and was read into the main Jupyter Notebook using Pandas.  The .csv files for each different county were merged to make single dataframes for easier analysis.  Here are a couple of dataframes that were created:

##### Grapi Dataframe
![Austin Grapi](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/grapi.png)

Grapi (Gross Rent as Percentage of Income) shows the number of households and what percentage of their income is used on their rent.  This combines both rented and mortgaged homes.

##### Housing Tenure
![Austin Housing Tenure](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/housing_tenure.png)

The housing tenure dataframe shows a simple view of mortgaged vs rented households.

##### Housing Value
![Austin House Value](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/value.png)

A quick overview of the number of households and their worth per year.

All of the data frames above were created and combined to complete the final analysis.

## % Spent on Rent for the Three Counties

Some simple pie graphs showing the % of income used on rent for each county in 2007 and 2016

![Hays 2007](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_hays_2007.png)
![Hays 2016](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_hays_2016.png)



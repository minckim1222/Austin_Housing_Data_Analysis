# Austin Housing Data Analsysis

#### An Overview of the Analysis Done
![Analysis Overview](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/housing_one_slide.jpg)
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
##### Hays County

![Hays 2007](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_hays_2007.png)
![Hays 2016](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_hays_2016.png)

##### Williamson County

![Williamson 2007](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_williamson_2007.png)
![Williamson 2016](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_williamson_2016.png)

##### Travis County

![Travis 2007](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_travis_2007.png)
![Travis 2016](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/morgage_percent_travis_2016.png)

##### The trend seems to be people are spending less of their income on housing.  

## Occupancy Bar Charts

Here is a bar chart that shows all of the housing units available, broken down into vacant and nonvacant.

![Austin Vacancy](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/total_occupancy_bar_chart.png)

Based on the data, there is a clear sign of growth in the Austin area.  The total amount of housing units are going up, while the number of vacancies is relatively stagnant.  This is a clear indicator that Austin is growing while limited the number of households leaving the area.

## Rent Vs Owned

Here is a bar chart splitting the number of households into rented vs owned.

![Austin Rent Vs Own](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/rented_vs_owned.png)

There is a slight trend towards owning over renting.  This can be an indicator that more people are planning to stay in Austin longterm

## Home Price VS Income Per Capita

Finally, here is a line graph showing the value of home compared to income per capita over the years.

![Austin Price VS Income](https://github.com/minckim1222/Austin_Housing_Data_Analysis_Final/blob/master/Saved_Pngs/percapita_vs_value.png)

This is a clear indicator that the housing market is outpacing wage growth.  The average cost of a home in Austin is steadily increasing, while the per capita income is staying relatively stable.  In the [% Spent on Income graph above](## % Spent on Rent for the Three Counties), you can see that more and more people are spending less of their income on housing.  It makes sense since the housing costs are outpacing wage growth that more people would try to find cheaper and more affordable housing.

## Final thoughts

The housing market in Austin is definitely on an incline.  The average price for a home in Austin continues to rise, and will continue to do so in the future.  Austin is drawing many people for many reasons: booming tech industry, laid back lifestyle, fantaastic music scene, and activities for a multitude of people.  






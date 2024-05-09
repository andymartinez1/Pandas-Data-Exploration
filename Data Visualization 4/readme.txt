For this data visualization, I chose to go with a dataset regarding US gas prices over the years. I think this fits into both the ethical and deceptive visualizations because there can be a narrative created to skew the numbers so people think prices are up or down. This can influence what customers are willing to pay for gas prices at certain gas stations or manipluate the citizens that there is less of an economic crisis than there really is. This answers the question of how gasoline prices fluctuate over time and where they typically sit at to help create predictions for future gas prices.

I created my visualizations by retrieving the dataset, "U.S. Gasoline and Diesel Retail Prices 1995-2021" from https://www.kaggle.com/datasets/mruanova/us-gasoline-and-diesel-retail-prices-19952021. I used 3 packages to complete my assignment: Pandas, Seaborn and MatPlotLib. I imported those packages and then loaded the above dataset into a Jupyter notebook. The dataset contained the following data:

    A1: Weekly U.S. All Grades All Formulations Retail Gasoline Prices (Dollars per Gallon)
    A2: Weekly U.S. All Grades Conventional Retail Gasoline Prices (Dollars per Gallon)
    A3: Weekly U.S. All Grades Reformulated Retail Gasoline Prices (Dollars per Gallon)
    R1: Weekly U.S. Regular All Formulations Retail Gasoline Prices (Dollars per Gallon)
    R2: Weekly U.S. Regular Conventional Retail Gasoline Prices (Dollars per Gallon)
    R3: Weekly U.S. Regular Reformulated Retail Gasoline Prices (Dollars per Gallon)
    M1: Weekly U.S. Midgrade All Formulations Retail Gasoline Prices (Dollars per Gallon)
    M2: Weekly U.S. Midgrade Conventional Retail Gasoline Prices (Dollars per Gallon)
    M3: Weekly U.S. Midgrade Reformulated Retail Gasoline Prices (Dollars per Gallon)
    P1: Weekly U.S. Premium All Formulations Retail Gasoline Prices (Dollars per Gallon)
    P2: Weekly U.S. Premium Conventional Retail Gasoline Prices (Dollars per Gallon)
    P3: Weekly U.S. Premium Reformulated Retail Gasoline Prices (Dollars per Gallon)
    D1: Weekly U.S. No 2 Diesel Retail Prices (Dollars per Gallon)

While this is all great and useful data, I only used the data from the A1, A2 and A3 columns. Because there were 1,361 date rows, I converted the date data and divided it by year, month and day. The purpose of this was to combine the days and months of the year into their respective years. Having 1,361 dates would make the visualization difficult to read and understand. I then took the date data from each year and got the mean of them respectively. 

For my ethical visualization, I used the US gas price data from 1995 to 2021. While it isn't very current, it still shows the price trend for a relatively big recent time point. My visualization shows the US gas prices for all formulations (Regular, Midgrade and Premium gasoline), conventional retail gasoline prices and reformulated (such as Shell V-Power gas) retail gasoline prices. I show all data points from the dataset in a clear and easy to read and constructive way. There is no misinterpretting the data and it shows storytelling of how the prices of gasoline have changed over the years. There are many factors as to why the prices fluctuate as much as they do, but this visualization stricly shows the factual data.

For my deceptive visualization, I only showed the prices for the years 2011 to 2016. As you can see in the line plot, the prices mostly go downwards only. This is an example of deceptive visualization because it can manipluate the audience to think gas prices only go down. This can make the US population think that the economy is only becoming more stable and benifitting them. I also left out the legend title and labels. This was done so that the main focus was on the gas prices going down as a whole. I also made the title much more vague so it's clear enough but without nearly as much useful information. I also made the chart taller to make the drop in prices seem much more substantial than they really are compared to the ethical visualization. The opposite can also be done with years 1995 to 2008 to justify gasoline price increases. There are many ways to use deceptive data visualizations to manipluate the audience into believing what you want them to believe.
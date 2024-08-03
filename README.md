# Advertising

"Advertising" dataset contains information about advertising spends across three different media channels (TV, Radio, and Newspaper) and their corresponding sales figures. 

Columns Description:

    TV: The amount of money spent on TV advertising for a particular product in thousands of dollars.
    Radio: The amount of money spent on Radio advertising for the same product in thousands of dollars.
    Newspaper: The amount of money spent on Newspaper advertising for the same product in thousands of dollars.
    Sales: The sales of the product in thousands of units.

The primary objective of this dataset is to analyze how different types of media advertising are correlated with product sales. This analysis can help in understanding which advertising channels are most effective and can provide insights for optimizing advertising budgets.

There are total 200 observations under each column. Now we have checked for missing values using df.info() command and found none. All the data types are of float type. 

We have displayed several plots to show that there is overall positive correlation with sales and mediums of advertising influencing sales. We have trained our model if 80% of its data andthe rest 20% is left for testing data. We have run Linear Regression model with R-squared value of 90.59% with a strictly positively sloping straight line with positive intercept. The errors follow normal distribution. 

From the above regression analysis, we can surely say that role of TV, radio and newspaper advertising have a significantly positive impact on sales.  

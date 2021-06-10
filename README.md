# ANALYSIS OF COMPANY XYZ SUPERMARKET DATA¶

Company XYZ owns a supermarket chain across Nigeria. Each major branch, located in 3 cities across the country, recorded sales information for 3 months to help understand sales trends and determine its growth due to the rise in supermarket competition. I will analyze this data set and bring out valuable insights for the company.


# Project Steps

### The following steps were taken in this analysis
1. Loading of the data set after setting the current working directory then combining files from each of the branches into a single data set.

2. Data exploration using different pandas attributes and methods.

3. Dealing with datetime features including converting relevant data columns to the datetime datatype and extracting time info from them.

4. Extracting unique values of the categorical data.

5. Further data exploration using groupby and aggregation functions.

6. Data visualization using different seaborn library plots.


# Insights

* **Fashion accessories** were the most patronized products while **Epay** was the most used payment channel.
* The city with the highest gross income is Port Harcourt with total gross income of #1895463.54.
* The Port Harcourt branch has the highest mean unit price, mean quantity and  mean ratings.
* There's a striking preference for cash payment among buyers of electronic accessories.
* Fashion accessories and home and lifestyle categories also show relative customer preference for payment using Epay
* There's a relative preference for Epay at the Lagos branch but cash at the Port Harcourt branch
* Females buy and spend relatively more on food & beverages as well as home & lifestyle products while males spend relatively more on health & beauty products
* Majority of shoppers spend 100,000 or less
* Product categories with the lowest unit price were on average purchased more; an example is the electronic accessories product line.

# Future Work

1. Analyzing individual branch's data set to discover possible peculiarities and insights.
2. Performing analysis on a data set spanning a longer time period

# Standout Section

* Viewing the header rows of the `csv files` prior concatenation.
* Viewing summaries for non-numerical data using the `.describe()` method.
* Preliminary attempts at answering other important questions.

# SuperMarket-Sell-using-Python-and-Pandas
Completed this hands on gudied project from Coursera on Cloud platform.
Tools used : Jupyter Notebook, Python, Pandas, numpy, pyplot, seaborn

Applied Exploratory Data Analysis (EDA) techniques :

• Task 1: Initial Data Exploration
• Task 2: Univariate Analysis
• Task 3: Bivariate Analysis
• Task 4: Dealing With Duplicate Rows and Missing Values
• Task 5: Correlation Analysis

Task 1: Initial Data Exploration
- import essential libraries such as NumPy, Pandas, Seaborn, Matplotlib 
- use Pandas to read in the data, get a brief glimpse of the first few rows, and calculate some quick summary statistics of the numeric columns.

Task 2: Univariate Analysis
• In this task, we conduct univariate analysis on both continuous and categorical variables.
• first plot the distribution of customer ratings with seaborn.
• use Pandas' .hist() method to plot the distribution for all numeric variables.
• Using Seaborn's .countplot() method, we see the frequency distribution of 'Branch' and 'Payment' which are categorical variables.

Task 3: Bivariate Analysis
• In this task, we conduct bivariate analysis on both continuous and categorical variables.
• use Seaborn to plot scatterplots and regression plots to identify the relationship between customer rating and gross income.
• Additionally, we use Seaborn to plot a boxplot to check the difference in aggregate sales figures between the three branches of supermarkets, and to compare sales patterns between men and women.
• plot a time series graph to check for trends in gross income over a period of three months.


Task 4: Dealing With Duplicate Rows and Missing Values
• In this task, identify and deal with duplicate rows and missing values in our dataset.
• calculate the number of duplicate rows and delete them using Pandas.
• do the same with missing values, but instead of deleting those rows, we replace missing values by the means of their respective columns.


Task 5: Correlation Analysis
• In this task, conduct correlation analysis on the numeric variables in our dataset.
• We then use pandas to calculate a correlation matrix to show all pairwise correlations of numeric variables.
• Finally, we use seaborn to plot the calculated correlation matrix as a heatmap that is easily interpretable.


The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data from kaggle.
data source: https://www.kaggle.com/aungpyaeap/supermarket-sales

Data Dictionary

    Invoice id: Computer generated sales slip invoice identification number

    Branch: Branch of supercenter (3 branches are available identified by A, B and C).

    City: Location of supercenters

    Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card.

    Gender: Gender type of customer

    Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

    Unit price: Price of each product in USD

    Quantity: Number of products purchased by customer

    Tax: 5% tax fee for customer buying

    Total: Total price including tax

    Date: Date of purchase (Record available from January 2019 to March 2019)

    Time: Purchase time (10am to 9pm)

    Payment: Payment used by customer for purchase (3 methods are available \u2013 Cash, Credit card and Ewallet)

    COGS: Cost of goods sold

    Gross margin percentage: Gross margin percentage

    Gross income: Gross income

    Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)





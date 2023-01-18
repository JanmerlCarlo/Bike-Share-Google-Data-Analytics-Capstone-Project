# Section 1: ASK

## What is the problem you are trying to solve?

Business Objective: To boost the number of annual memberships by converting casual riders to annual members.

## How can your insights drive business decisions?

With the help of visualizations and important findings, an attempt will be made to determine patterns in how annual members use bicycles differently from casual riders. This information will be used to provide recommendations that the company can take into account in an effort to increase annual memberships.

# Section 2: PREPARE

The dataset required for this business objective should be of the past 12 months. Here, we are considering data from January 2022 till December 2022.

Credibility of the data is ensured by the fact that it was made available by Motivate International Inc. under the proper license. You can investigate how various client types utilize Cyclistic bikes using this open data.

The data file had various folders for each month of a certain year, and quarterly data organized by year was also made available.

Since we could only take into account information from the previous 12 months, I retrieved the necessary csv files and put them all in one folder for better access and use.

# Section 3: PROCESS

For working with data, I favor Python since it is more widely available and simpler to use.

Any analysis should begin with the import of the necessary libraries into the notebook.

Some of the important libraries are:

* Pandas - Pandas allows importing data from various file formats such as comma-separated values (CSV), JSON, SQL, Excel. Pandas allows various data manipulation operations such as merging, reshaping, selecting, as well as data cleaning, and data wrangling features.
* Numpy - It can be used to perform a number of mathematical operations like trigonometric, statistical, and algebraic on arrays.
* Matplotlib and Seaborn - It is used to create graphical analysis of the data.
* Datetime - These classes provide a number of functions to deal with dates, times and time intervals.

# Section 4: ANALYSIS



It is crucial to aggregate, organize, and arrange the data after it has been cleaned. Here we need to perform calculations(descriptive analysis) and understand the trends present in the data.

# Section 5: SHARE

To plot visuals, we employ python tools like seaborn and matplotlib.

Visualizations allow us to see that the proportion of casual riders to annual members is roughly equal. A total of 59.8% of the population are annual members.

# Section 6: ACT

* 1. Based on the analyses, it can be seen that there are more annual riders than annual members. We can raise the cost of casual rides (which will help bring in more money initially) while simultaneously lowering the annual membership fee. More riders will become annual members as a result of this.
* 2. As seen, Fridays are the day when most casual bikers ride. To draw customers, we can offer exclusive weekend discounts on yearly memberships. At the same time, we can promise annual membership holders that bikes will be available on weekends, but we can't promise the same to casual riders.
* 3. By making the entire process simple and available online, we can help speed up the process of obtaining an annual membership. Conversely, casual cyclists should get their bikes from bike shops. Although this may encourage some customers to sign up for annual memberships, it will ultimately damage the company's reputation. So we should make an effort to avoid falling for this anti-pattern.


```python

```

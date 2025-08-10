# **Unicorn Companies EDA**

## **Overview**
In this project, we are conducting an exploratory data analysis of Unicorn Companies dataset to generate insights into how and when companies reach the unicorn status ($1B). We identify new business oppurtunities by gaining insights into most profitable industries and getting the list of current companies valued at more than $1 billion. This helps us learn about businesses and industries that are profitable. 

## **Data Dictionary**
This project uses a dataset called `Unicorn_Companies.csv` from [Kaggle](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies?select=Unicorn_Companies.csv). It represents a list of private companies with a valuation of over 1 billion dollars. The data includes the name of the country where the company was founded, its current valuation, funding, industry, top investors, year it was founded, and the year it reached a 1 billion dollar valuation.

The dataset contains:

**1,074 rows** – each row is a different company

**10 columns**

| Column name | Type | Description | 
|-------------|------|-------------|
| Company | str | Company name |
| Valuation | str | Company valuation in billions of dollars|
| Date Joined | datetime | The date in which the company reached 1 billion dollar in valuation |
| Industry | str | Company industry |
| City | str | City the company was founded in |
| Country/Region | str | Country the company was founded in |
| Continent | str | Continent the company was founded in |
| Year Founded | int | Year the company was founded |
| Funding | str | Total amount raised across all funding rounds in dollars |
| Select Investors | str | Top investing firms or individual investors |


## **Steps**
### **1. Imports**
-  Import libraries and packages
-  Load the dataset into a DataFrame

### **2. Data Cleaning**
- Modify the data types
- Create new columns
- Check for duplicate rows and null values in the data
- Make corrections by identifying bad data
- Handle issues with column labels

### **3.  Data exploration**
- Assess the size of the dataset
- Determine the shape of the dataset
- Get basic information about the dataset
- Check for duplicates in the data
- Sort the data
- Create new columns
- Gain insight on industry-level and country-level data
- Determine the average and total valuation of companies with respect to industry, continent and country.
- Determine the number of companies founded each year
- Gain more insight on 2021
- Observe weekly trends
- Compare trends over time

### **4. Results and evaluation**
- Visualize the total valuation and number of companies with respect to country using bar chart
- Visualize the total valuation and number of companies with respect to industry using bar chart
- Visualize the number of companies with respect to the year founded using histogram
- Visualize the average valuation over the quarters and weeks in 2020 and 2021 using bar chart
- Visualise distribution of years to become unicorn with respect to month the company joined the unicorn status using boxplot
- Visualise years taken to join unicorn status with respect to year the company was founded using bar chart

## **Findings**
- There are 1074 unicorn companies represented in this dataset.
- The oldest company in the list was founded in 1919 and the latest company in the list was founded in 2021.
- The United States, China, India, and the United Kingdom have the highest total company valuation.
- Europe has a lot of unicorn companies in a concentrated area.
- "Artificial Intelligence" industry has the highest average valuation.
- 2015 is the year when the most number of unicorn companies were founded. 
- Many of the unicorn companies that were founded in 2021 were founded in the United States and belong to "Fintech" and "Internet software & services" industries. 
- The box plot created shows that companies that become unicorns in the months of September and October have a smaller median value for how long it took to become unicorns.
- One of the bar plots created shows that the average valuation of companies that joined in 2020 is highest in the third quarter of the year, whereas the average valuation of companies that joined in 2021 is highest in the first quarter of the year. 

## **Recommendations**
- According to exploratory data analysis that was conducted on unicorn companies dataset, companies that joined in the months of September and October tended to take less time to become unicorns.
- Another finding was that many of the unicorn companies that were founded in 2021 were founded in the United States and belong to "Fintech" and "Internet software & services" industries. So to invest in companies founded in 2021, it would be a good idea to consider companies that belong to these industries, as they may be strong candidates for becoming unicorns.
- It was also discovered that the average valuation of companies that joined in 2021 is highest in the first quarter of the year, and the average valuation of companies that joined in 2020 is the third quarter of the year. When considering companies that newly join in the future, it would be worth closely looking at companies that join in the first and third quarters of the year. 
- The data can be analyzed further to gather more insights that are specific to the interests of the relevant stakeholders.

## **Next steps**
- Analyze the data with respect to funding of unicorn companies.
- Analyze the data with respect to investors of unicorn companies.
- Determine which companies have higher valuation but do not have as many investors currently.

## **Possible questions**
- How many rounds of funding did each company require and when did this funding take place?
- Have any of these unicorn companies acquired other companies along the way?
- Which companies acquired other companies, which companies did they acquire, and when did the acquisitions take place?
- What factors were considered while collecting this data? Is there any bias in the data collection process?

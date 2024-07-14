# Amsterdam-Airbnb-Data-Analysis
## Project Motivation
The purpose of this analysis is to generate insight into the Airbnb market in Amsterdam in various aspects, including the number of listings, price, hosts, and the neighborhoods. To achieve this, Microsoft Power BI was used both for ETL and data visualization processes. Before doing the analysis, several questions were defined to have a clear object. These questions are:
1. **Overview of Airbnb:**
   * What is the number of total listings so far?
   * What is the average price in total (i.e., in Amsterdam)?
   * What is the trend of total listings throughout the years?
   * What are the most popular neighborhoods in terms of listings?
2. **Host & Property Analysis:**
   * Who are the most popular hosts and what are the average prices for their respective properties?
   * What is the distribution of property types in general?
## Installation
This project uses Microsoft Power BI as the main tool for data analysis. Therefore, there is no need to install any additional packages.
## Data
The data was obtained from the [Inside Airbnb](https://insideairbnb.com/get-the-data/) website. As of this writing, the date of the updated data for Amsterdam is 11 May, 2024. From the 7 datasets provided under the "Amsterdam, North Holland, The Netherlands" section, two datasets were chosen:
* ```listings.csv``` with the all listings in Amsterdam.
* ```reviews.csv``` with the all reviews of hosts with their respective dates.
## Results (Answering the Project Questions)
### General Dashboard:
![Image of Amsterdam Airbnb Market](https://github.com/azizbarank/Amsterdam-Airbnb-Analysis/blob/main/images/amsterdam.jpg)

1. **What is the number of total listings so far?:**

There are **5444** Total listings in total.

2. **What is the average price in total (i.e., in Amsterdam)?**

The average price in general in Amsterdam is **€256.73**.

3. **What is the trend of total listings throughout the years?**

![Trend of Total Listings](https://github.com/azizbarank/Amsterdam-Airbnb-Analysis/blob/main/images/total_listings.jpg)

As can be seen from the image, there is a general stalemate between the years 2014-2021. In fact, there is a slight decrease during the COVID period (e.g., Total listings in 2019: 43, in 2021: 23). However, after the end of it, there is an increase between 2021 and 2022 (i.e., 23 to 191) and after that there is a sharp increase until 2023 (i.e., 2235 listings in 2023). Finally, after 2023, there seems to be a slight increase again but since the dataset ends in May 2024, we cannot see the whole change.

4. **What are the most popular neighborhoods in terms of listings?**

![Image of Neighborhoods](https://github.com/azizbarank/Amsterdam-Airbnb-Analysis/blob/main/images/neighborhoods.jpg)

Apparently, the most popular neighbordhood with 887 listings is "De Baarsjes - Oud-West". Centrum-West and De Pijp-Rivierenbuurt follows it, respectively, with the Centrum-Oost and Zuid coming after them.

5. **Who are the most popular hosts and what are the average prices for their respective properties?**

![Image of Popular Hosts](https://github.com/azizbarank/Amsterdam-Airbnb-Analysis/blob/main/images/hosts.jpg)

The popularity was based on the number of reviews these places get in total. Therefore, given this, the most popular host seems to be "Concious Hotel the Tire Station", which is a hotel, rather than an individual. It got 3299 reviews so far. The host "Generator" is similarly a hotel-hostel, which comes right after it. When we look at the prices, even though we can see some hosts charge higher than their respective popularity, there is not much of a difference in terms of average price between places, which mostly varies between €100-€200.

6. **What is the distribution of property types in general?**

You can see the numbers of each room type in the table below:

|       Room Type    | Number of Listings |
| -----------------  | -------- |
|Entire Home/Apt     | 3978     |
|Private Room        | 1407     |
|Hotel Room          | 36       |
|Shared Room         | 23       |
|**Total**           | **5444** |

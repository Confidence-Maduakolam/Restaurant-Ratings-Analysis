# Mexico Restaurant-Ratings-Analysis

![mexico wallpaper](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/652b194f-8f25-4007-b933-d38393b720e1)

### Table of contents

- [About Project](#about-project)
- [Data Cleaning and Transformation](#data-cleaning-and-transformation)
- [Data Modelling](#data-modelling)
- [Data Visualisation](#data-visualisation)
- [Full DashBoad](#full-dashboard)
- [Recommendations](#recommedations)
  
### About Project 
##### Restaurant Rating:

This data set is called the restaurant rating dataset which contains information about restaurants in Mexico. A customer survey was carried out in this city in 2012 to collate information about each restaurant, their cuisines, information about their consumers and the preferences of the consumers. There are other additional information you will find in this dataset when exploring it. You are contracted as a Data Analyst to analyze and draw out meaningful insight from this dataset which would aid business entrepreneurs and investors in making more informed decisions. Using skills learnt from the data Bootcamp, To analyze the dataset and provide answers to the questions listed below. 

1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?
2.  What are the consumer demographics? Does this indicate a bias in the data sample? 
3.   Are there any demand & supply gaps that you can exploit in the market?
4.   If you were to invest in a restaurant, which characteristics would you be looking for?

### Data Cleaning/Transformation

After examining and extracting the data from the 'Restaurant_Ratings.zip' file, which contains five CSV files (Restaurants, Restaurant cuisines, Ratings, Consumers, and Consumers preference), I uploaded the data into Power Query Editor for cleaning and transformation. In this process, I replaced null values with 0 and utilized the first row as headers for certain datasets. After the data cleaning, I observed that some datasets share one or two connections, notably the consumer_id and restaurant_id, which served as the primary key for merging all the datasets as seen below.

![merge 1](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/06da7489-5503-4314-9a60-c4fa9fe61d15)|![merge 2](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/288d7b6b-dc15-4a9d-bf84-d07e0c6417a1)

![merge 3](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/ce6ea31e-309b-471f-94e9-1ad433073e18)|![merge 4](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/99c660b0-301a-4b39-b868-7829c45c9de8)

### Data Modelling
After merging the data the result is as shown below, showing the connections for each table

![res model view](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/71ae4e43-98e5-4d1f-b729-53dba3c350a9)


### Data Visualisation

![Res 1](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/802ded6c-2cdc-4eb5-97df-3f8acd19c8b4)


The above dashboard is used to answer the Question 1 and 2 which are:

1. What can you learn from the highest rated restaurants? Do consumer preferences have an effect on ratings?
   

Overall Ratings by Restaurant: The highest rated restaurant is "Tortas Locas Hipocampo" with a rating of 48, followed by "Puesto De Tacos" with 41, and "Cafeteria Y Restaurante El Pacifico" with 33. This suggests that "Tortas Locas Hipocampo" is performing exceptionally well in terms of customer satisfaction.

Consumer ID by Preferred Cuisine: The most preferred cuisine is Mexican, with 97 consumers preferring it, followed by American (11 consumers), and then Cafeteria and Pizzeria (9 each). This indicates a strong preference for local cuisine among the consumers, which might be influencing the high ratings for restaurants that offer Mexican food, like "Tortas Locas Hipocampo."

2. What are the consumer demographics? Does this indicate a bias in the data sample?
   
   
Restaurant Food Ratings by Age, Occupation & Marital Status: The table shows a variety of consumers, mostly younger (ages 21–25), students, and single. This might indicate a bias towards younger, single individuals in the data sample, which could affect the generalizability of the results to other demographic groups.

Service Rating by Smoking Allowed: Most of the service ratings are from places where smoking is not allowed (73.46%), which might skew insights about consumer preferences related to smoking areas.

Average Overall Rating by Alcohol Service: The majority of ratings come from restaurants that offer "Full Bar" (34.29%) followed by those with "Wine and Beer"(33.8%). Restaurants with No alcohol service have the least ratings (31.9%).

![Res 2](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/22d0f613-c531-4817-825f-e974228d43f5)


The above dashboard is used to answer the Question 3 and 4 which are:

3. Are there any demand & supply gaps that you can exploit in the market?
   
   
Service Rating by Alcohol Service: As shown on the dashboard (63.19%) of restaurants offer no alcoholic services, which receive a higher service rating. This suggests a strong market preference for restaurants with no alcohol service options followed by 29.46% restaurant that of wine and beer services.

Count of Service Rating by Smoking Allowed: Most restaurants (74.16%) do not allow smoking, aligning with a general trend towards non-smoking environments. This could indicate a preference or regulatory environment favoring non-smoking establishments.

Preferred Cuisine by Budget: Mexican cuisine shows a high preference across all budget categories, especially in the medium budget range. This indicates a robust demand for Mexican cuisine Other cuisines like American, Cafeteria, and Pizzeria also show some demand, particularly in the medium budget range.

Overall Rating by Name and Price: Restaurants like "Tortas Locas Hipocampo" and "Puesto de Tacos" have high ratings and are likely priced low to medium. This suggests a gap in the market for high-quality, affordable dining options.

4. If you were to invest in a restaurant, which characteristics would you be looking for?
   
   
Characteristics to Consider:

•Alcohol Service: Opt for a full bar setup to attract a larger clients, as indicated by the high service ratings for such establishments.

•Smoking Policy: Invest in a non-smoking restaurant to align with the majority preference and possibly regulatory trends.

•Cuisine Type: Mexican cuisine is a safe bet given its widespread popularity. However, offering a unique twist on traditional dishes or high-quality ingredients could differentiate the restaurant.

•Price Point: Targeting the medium price range could be optimal, as it appears to cater to the largest segment of the market while still allowing for profitability.

•Location: Choose locations in cities with higher overall ratings to capitalize on existing positive perceptions of dining experiences in those areas.

By focusing on these characteristics, an investment in a restaurant is more likely to succeed, tapping into established market preferences while offering distinctive qualities that can set the restaurant apart from competitors.

### Full DashBoard

![Res 3](https://github.com/confilovydovy/Restaurant-Ratings-Analysis/assets/7013375/e9d1aead-2313-4f01-bec3-19f0e4f8c9ac)


### Recommendations

- Restaurants should consider focusing on Mexican cuisine or incorporating Mexican dishes into their menu to attract more customers, as there is a clear preference for this cuisine.

- "Tortas Locas Hipocampo" could be studied as a case study by other restaurants to understand what practices are leading to such high consumer satisfaction

- Future surveys should aim to include a more diverse range of ages, marital statuses, and occupations to ensure a more representative data sample.

- Consider analyzing the impact of allowing smoking on customer satisfaction and see if adjustments in policy might attract a different demographic.

- Exploit Full Bar Services Given the high service ratings for restaurants with full bar services, opening a restaurant with a comprehensive range of alcoholic beverages could attract more customers.

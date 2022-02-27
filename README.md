# Module-9-Challenge-SurfsUp
## 1. Project Overview
### Background:
W. Avy would like some assistance in reviewing temperature trends before opening up a surf shop, specifically the temperature data in Oahu, Hawaii to see if her idea of a surf and ice cream shop would be viable year-round. I.E. are the temperature ranges in the peak of summer and winter in the ideal range for a Surfing and Ice Cream bussiness to thrive.
### Purpose:
The Code is intended to filter the date of June and the temperature readings of June from a SQLite file into a list and convert said list into a dataframe. Then to retrieve the summary statistics from the dataframe for the temerature measurements. Rinse and repeat for the month of December. Lastly, to convert said summary statistics into insight for W. Avy.
## 2. Results
Foreward I lived in Houston and attended the University of Houston for my undergrad. Having studied in sight of an ice cream place on campus. While demand for ice cream increases during summer months, especially hot months. Winter Months still had high demand as in the Gulf Coastal winters typically averaged around 45°F and people still got ice cream to a decent extent. So I will consider 45°F a range in which people will still buy ice cream to a stable amount.
### June :
- Minimum temperature is 64°F, which is above the 45°F threshold I set up, meaning there will still be demand on the coldest days of summer. This temperature range will also work for the surfing aspect as it leaves the water to be cool and great for surfing.
- Average temperature is 75°F which is a comfortable temperature for ice cream and surfing, meaning on the average day the shop will be in a comfortable temperature range.
- Maximum temperature is 85°F which isn't uncomfortable hot, and will lead to an increase in demand for ice cream and the surfing.
- The Interquartile Range is between 73°F and 77°F which is a fully comfortable range 
Table 9.1:

![image](https://user-images.githubusercontent.com/71575748/155899541-f38c8626-0ced-4e88-8b22-16782ba406c8.png)

### December :
- Minimum temperature is 56°F, which is above the 45°F threshold I mentioned. Meaning on the coldest days of winter, there will still be adacquate demand for Ice Cream. In terms of surfing, its above a 50°F threshold meaning on a sunny day demand for surfing will still be adacquate.
- Average temperature is 71°F is a comfortable temperature for ice cream and surfing
- Maximum temperature is 83°F is close to the maximum temperature during the summer, which would make sense for Hawaii's climate. This Temperature max is adequate for ice cream and surfing.
- The Interquartile Range is between 69°F and 74°F which is a fully comfortable range for surfing and ice cream.

Table 9.2:

![image](https://user-images.githubusercontent.com/71575748/155899778-b52e3927-2dc4-49d3-8747-abd2bc816ed8.png)

## 3. Summary
In conlusion, the temperature is in good range for surfing and ice cream for the whole year. Under the assumption of fair weather in terms of other aspects such as wind and precipitation. Other queries to be made would be looking into these aspects such as wind speed and precipitation. Since wind speed will have an effect on sales during cold days and precipitation will always have an effect on demand for both.

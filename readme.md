I chose the Ford GoBike System Dataset. I focused data for 2019.

------

Main findings:

1. Question 1: **When are most trips taken in terms of time of day, day of the week, or month of the year?**

In terms of:
- Time of day: 17:00
- Day of the week: Tuesday
- Month of the year: July

**Other interesting insights**:

- Month:

The least popular month is December.

July and March represent more than 20% of the trips in 2019.

- Day of the week:

Weekend days have around half less trips than regular week days.

- Time of day:

3:00 is the least popular time.

There are two clear peaks between 07:00 and 10:00 and 16:00 and 19:00. This represent 54.2% of the trips in a day on average.


2. Question 2: **How long does the average trip take?**

The average trips takes around 500 seconds. This is after wrangling the data.

The orginal dataset shows an average of 800 seconds. However, this includes many, very high outliers.

**Other interesting insights**:

Most trips fall into the interval of 60 to 10000 seconds.

The largest amount of trips fall into the interval of 300 to 700 seconds.


3. Question 3: **Does the duration of a trip per month, weekday or hour depend on if a user is a subscriber or customer?**

Yes. The average duration for the subscriber is lower in all cases.

**Other interesting insights**:

Less than 20% of the users are customers.

- **Additional Insights**

The heat map shows that the trips' starting locations are in San Francisco, Oakland and San Jose.

------

I chose the results that were essential to answer the questions to include on my presentation.

------

Resources:

    Combine CSV files: https://www.freecodecamp.org/news/how-to-combine-multiple-csv-files-with-8-lines-of-code-265183e0854/
    Convert start_time to string months and weekdays: https://strftime.org/
    Heat map: https://ipyleaflet.readthedocs.io/en/latest/api_reference/heatmap.html

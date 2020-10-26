# BAY WHEELS DATA ANALYSIS

Over the last decade, bicycle share networks have increased in number and prevalence in cities around the world. Bicycle share services allow users to borrow short-distance bicycles, normally 30 minutes or less. Thanks to the increase of information technology, it is easy for the system user to enter the dock inside the system to unlock or return bicycles. These solutions also have a range of data that can be used to analyze how these bike sharing networks are used.

Bay Wheels (known as Ford GoBike) is the Bay Area's new bike sharing scheme, with thousands of shared bikes to be used around San Francisco, East Bay and San Jose. The rental bikes was built with comfort in mind. It's a fun and inexpensive way to travel around town. It also offers a single ride of $2 a day that's ideal for a one-way trip, a monthly membership of $15 a month for a decent price for residents, and a 10 dollar entry pass that's perfect for exploring.

In this project, I will perform an exploratory analysis on data provided by Bay Wheels (Ford GoBike), a bike-share system provider.

About Dataset: I chose [Ford GoBike System Data (Bay Wheels Dataset)](https://s3.amazonaws.com/fordgobike-data/index.html) in Udacity (which is now can be accessed as Bay Wheels) as my source data This data set includes information about individual rides made in a bike-sharing system. Multiple data files need to be joined together for a full year’s coverage.

The features included in the dataset :

- Trip Duration (seconds)
- Start Time and Date -
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

## **Summary of Findings**

**1. Univariate Exploration:**

The number of trips gradually decreases when the weather becomes colder. During the day, there are more trips in the morning and afternoon than the night. Also, there are more trips during the weekdays and less trips during the weekends. It makes sense that there are more subscribers than customers when we check the [pricing](https://www.lyft.com/bikes/bay-wheels/pricing).

**2. Bivariate Exploration:**

There is an interesting difference between user tpye and duration of trips. Weekdays have the most trips than weekends. There is a decrease trend subscriber count in the winter months every year. And 2020, with the additional affect of the global pandemic, fall in the subscribers can be seen.

**3. Multivariate Exploration:**

Separating user types, customers and subscribers, gives more insights. The number of trips increases in the tourist attractions like ferry building and Embarcadero. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers.

## **Key Insights for Presentation"**

For Data Analysis, First I started exploring dataframe differences for last three years.
For Analysis purpose, I've investigated data quality and tidiness issiues.
For Univariate Exploration, I started exploring data by Monthly,Weekly,Hourly Bike Trends and Percentage of User Types.
In Bi-variate Exploration, I analyzed by calculating Percentage of Subscribers and Customers and then Monthly,Weekly and Hourly usage by user types and also calculated Average Trip duration and distance for both Subscribers and Customers.
In Multi-variate Exploration, I extended analysis by taking three variables using different user types' weekly trends. (Subscribers and Customers). Finally, I used heatmap to show when bikes are high in demand during Weekdays,Different hours by user types(Subscribers and Customers).

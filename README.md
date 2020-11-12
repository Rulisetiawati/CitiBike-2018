# CitiBike-2018

Citi Bike is a bicycle sharing system established in 2013 in New York City. As of now, the nation’s largest bike-sharing system has 12,000 stations across Manhattan, Brooklyn, Queens, and Jersey City.  Riding a bike is fun and healthy exercise. Additionally, in urban areas like NYC, bike-sharing can also serve as a time-effective way of moving around tightly packed areas. By using a smartphone, users can download the free Citi Bike app and locate the nearest stations as well as the number of bikes available at each station. A single ride costs $3/ trip, up to 30-minute rides. Daypass costs $12/day, unlimited 30-minute rides in a 24-hour period. The annual membership costs $169/year, unlimited 45-minute rides. 

For the purpose of this project, I have analyzed the use of Citi Bike in 2018 from multiple aspects, including but not limited to:

- What are the total trips monthly throughout the year of 2018?
- What are the total trips for each hour of the day for every month in 2018? Are there differences in the winter months vs any other months?
- What do the total trips look like on the weekday vs weekend? How do weekday vs weekend trips look in Fall, Spring, Summer, and Winter?
- What is the proportion of bike usage for each day of the week based on the user type (customer vs subscriber)? How does it look like based on gender?

I am getting my data from Citi Bike’s system data (https://www.citibikenyc.com/system-data). Data for each trip is made available on the Citi Bike’s website. Each file records monthly data. Each data file is huge, but for this project, I will only be analyzing the data for 2018. Each trip record includes:

* Trip duration
* Start time
* Stop time
* Start station ID
* Start station name
* Start station latitude
* Start station longitude
* End Station ID
* End Station Name
* End Station Latitude
* End Station Longitude
* Bike ID
* User type
* Birth year
* Gender

Packages I am using for this project:
* knitr
* dplyr
* tidyverse
* lubridate
* maps
* tmaptools
* ggmap
* rmap

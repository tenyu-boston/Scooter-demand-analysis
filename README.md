# Scooter-demand-analysis
This analysis is based on a real world dataset from a company.
Due to the confidentiality, the latitude and longitude value is NOT shown.
The results mainly demonstrate data visualization technique and machine learning technique

# Results explanations for corresponding chart shonwn in 'Data summary' file

SUMMARY of the analysis
1. Depends on the location, the demand of scooter varies significantly. The number of demand is highly correlated with population density.However, there is no correalation between the location and travel time.
2. Social movement, events or other activities can potentially increase the customer demand significantly



(1) Overview of the dataset
The data is a single csv file includes the following columns
1. VEHICLENUMBER (the unique ID for a scooter)
2. LONG (Longitude)
3. LAT (Latitude)
4. RIDEID (Unique ID for the ride)
5. BATTERYPCT (The battery reading on the vehicle at the time of the event)
6. AREAID (ID for the area the event occurred)
7. EVENT_TYPE (The type of event being recorded)
8. VEHICLETYPE (The type of vechile. A shared scooter or bike)


(2) Trips number per day
Key findings
1. Weekened has more riderships than weekday
2. Social event, social movement or other activities could impact to the number of ridership. In this case, 8/29 (Sat) and 8/30 (Sun) have significant ridership than other weekends.

(3) Distribution of trip bydifferent time period (1-hour interval)
Key findings
1. High ridreship from late afternoon to night, in this case, it is between 16:00 and 20:00
2. There was no ridership between 22:00 to 3:00

(4) Relationship between trip number and mdedian travel time per trip
Key findings
1. Total ridership per hour between weekday (5 days) and weekend (2 days) is similar 
2. As customer demand increases, the median travel time increase as well (proportional increase )

(5) Demand per unique scooter across a whole month
Key findings
1. Total trip using scooters is 18853 in a whole month (August), the average travel time is 24 minutes, and the median travel time is 12 minutes
2. 65% (530/817) of scooters are not used frequently because they are used less than 31 times per month. Assume that we want each scooter to be used every day, this result shows that 65% of scooters did not satisfy this goal.

(6) Distribution of travel time
Key findings
1. Most of scooters are used less than 15 minutes. Around 60%.
2. 90% of trips were completed no longer than 60 minutes.

(7) Pick up location for each trip and corresponding travel time
Key findings
1. Many scooters are used in the downtown and park areas.  
2. Since some of areas do not have high ride demand, there is more room to relocate the location of scooters based on the real-time on-demand.

(8) Using k-means to cluster into 3 groups (3 dimensions) bsaed on pick up location (longitude & latitude) and     travel time of trips
Travel time DOES NOT depend on the pick-up location. Therefore, it would be very difficult to predict the travel time of trip based on the scooter's pikc up location. 

(9) Using k-means to cluster into 4 groups based on two dimensions (Longtitude and Latitude)
Key findings
1. A group with green color shows the college areas, and the rest of groups show downtown and park areas. This indicate that college students do not use a lot scooters on the campus, but on the downtown area (or park).
2. There are more ways to cluster, so 4 groups is just an example. 

(10) Travel time distribution based on each cluster
1. Customers who pick up scooters in urban, park areas tend to travel longer than those in non-urban area (Compare class 1&3 to class 4)
2. More customer demand in urban area
3. scooters located far away from urban area, they are less likely to be used




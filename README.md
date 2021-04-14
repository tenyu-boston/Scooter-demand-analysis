# Scooter-demand-analysis
This analysis is based on a real world dataset from a company.
Due to the confidentiality, the latitude and longitude value is NOT shown.
The results mainly demonstrate data visualization technique and machine learning technique

# Results explanations for corresponding chart shonwn in 'Data summary' file

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
Two key findings
1. Weekened has more riderships than weekday
2. Social event, social movement or other activities could impact to the number of ridership. In this case, 8/29 (Sat) and 8/30 (Sun) have significant ridership than other weekends.

(3) Distribution of trip bydifferent time period (1-hour interval)

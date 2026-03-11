# Village Agriculture Report
 ##  1. Projects Overview and Objective:
The primary objective of this project is to analyze the relationship between household livelihood patterns (farm vs non-farm) and availability of agricultural infrastructure across different states and years (2020) in India. 

The analysis aims to identify structural patterns, regional disparities, and infrastructure-level differences using Python-based data analysis techniques.
 ## 2. Data Sources:
**Source Description and Timeline:**

SOURCE: India Data Portal                         
LOCATION : India                                       
YEAR : 2020  

### **Domain:**  Rural Socioeconomic Research
## 3. Problem Statement:
- To examine how village size influences the availability of agricultural infrastructure and the resulting impact on livelihood patterns.
- To investigate how variations in water-related infrastructure affect the stability of farm-based livelihoods and reduce reliance on non-farm activities.
- To identify regional disparities in infrastructure distribution across states and their role in shaping rural economic opportunities.
- To assess how institutional support systems, such as farmers’ collectives, influence farm engagement, particularly in larger villages.
- To uncover patterns linking infrastructure quality and livelihood diversification, providing actionable insights for balanced rural development planning.
## 4. Attribute (Column /Features) Details: 
| Attribute Name | Data Type | Description |
|---------------|------------|-------------|
| ID | Numeric (Integer) | Unique identifier for each record | 
| Year | Date(Year) | Year of the survey/data collection (2020). |
| State_Code | Numeric (Integer) | Numeric code representing the state. |
| Transport_Type | Categorical | Type of transport (Bus, Train, Tram, Metro) |
| Route_No | Categorical | Route number assigned to the trip |
| Origin_Station | Categorical | Starting station of the trip |  
| Destination_Station | Categorical | Ending station of the trip |
| Scheduled_Departure | Time | Planned departure time |
| Actual_Departure | Time | Actual departure time recorded |
| Departure_Delay_Min | Numeric (Integer) | Delay in minutes for departure |
| Scheduled_Arrival | Time | Planned arrival time |
| Actual_Arrival | Time | Actual arrival time recorded |
| Arrival_Delay_Min | Numeric (Integer) | Delay in minutes for arrival |
| Weather_Condition | Categorical | Weather during the trip (Rain, Fog, Storm, Clear, etc.) |
| Temperature_C | Numeric (Float) | Temperature in Celsius |
| Humidity_% | Numeric (Integer) | Humidity percentage
| Wind_Speed_Kmh | Numeric (Integer) | Wind speed in km/h |
| Precipitation_mm | Numeric (Float) | Rainfall or precipitation level |
| Event_Type | Categorical | Type of public event (Concert, Festival, Sports, Protest, None) |
| Event_Attendance_Est | Numeric (Integer) | Estimated number of attendance |
| Traffic_Congestion_Index | Numeric (Integer) | Congestion level on the route |
| Holiday | Categorical | Indicates if the day is a holiday or not |
| Peak_Hour | Categorical | Whether the trip occurred during peak or off-peak hours |
| Weekday | Categorical | Name of the day (Monday–Sunday) | 
| Day_Type | Categorical | Indicates whether it is a weekday or weekend |
| Season | Categorical | Season during the trip (Winter, Summer, etc.) |
| Delayed | Categorical (Yes/No) | Final label indicating if the trip was delayed |

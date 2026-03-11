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
| Year | Date(Year) | Year of the survey/data collection (2020) |
| State_Code | Numeric (Integer) | Numeric code representing the state |
| State_Name | Categorical | Name of the State |
| District_Code | Numeric (Integer) | Numeric code representing the district |
| District_Name | Categorical | Name of the District |  
| Block_Code | Numeric (Integer) | Numeric code representing the block |
| Block_Name | Categorical | Name of the Block |
| GP_Code | Numeric (Integer)  | Numeric code for Gram Panchayat (local village council) |
| GP_Name | Categorical | Name of the Gram Panchayat |
| Village_Code | Numeric (Integer) | Unique numeric code for the village |
| Village_Name | Categorical | Name of the Village |
| Tot_HH | Numeric (Integer) | Total number of households in the village |
| HH_Farm_Activities | Numeric (Integer) | Number of households engaged in farm-based activities |
| HH_Non_Farm_Activities | Numeric (Integer) | Number of households engaged in non-farm activities |
| Avail_Govt_Seed_Centres | Categorical | Availability of government seed centers (Yes/No) |
| Avail_Watershed_Dev_Proj | Categorical | Availability of watershed development projects (Yes/No) |
| Avail_Community_Rain_Water_Harvesting_System | Categorical | Availability of community rainwater harvesting systems (Yes/No) |
| Avail_Farmers_Collective | Categorical | Availability of farmers’ collectives (Yes/No) |
| Avail_Warehouse_Food_Grain_Storage | Categorical | Availability of food grain storage warehouses (Yes/No) |
| Avail_Primary_Processing_Facilities |Categorical | Availability of primary agricultural processing facilities (Yes/No) |
| Avail_Custom_Hiring_Centre | Categorical | Availability of custom hiring centers for agricultural machinery (Yes/No) |
| HH_Farm_percent | float | Percentage of households engaged in farm activities |
| HH_Non_Farm_percent | float | Percentage of households engaged in non-farm activities | 
| Infra_Count | Numeric (Integer) | Total number of available infrastructure facilities in the village (derived count). |
| Infra_Level | Categorical | Categorical classification of infrastructure level (e.g., Low, Medium, High) |


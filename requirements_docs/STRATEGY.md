# Strategy Requirements Document: Cyclistic

## Sign-off Matrix
|Name               |Team Role                  |Date         |
|:-----------------:|:--------------------------|:---------:|
|user|IT | 2024|

## Propser: Cyclistic’s Customer Growth Team

## Status: Completed

## Datasets
1. Primary: [NYC Citi Bike Trips](https://console.cloud.google.com/marketplace/details/city-of-new-york/nyc-citi-bike?inv=1&invt=AbkizA&project=encoded-shape-438718-s6)
2. Secondary: [Census Bureau US Boundaries](https://console.cloud.google.com/marketplace/product/united-states-census-bureau/us-geographic-boundaries?inv=1&invt=AbkizQ&project=encoded-shape-438718-s6)

## User Profiles
- Sara Romero, VP, Marketing
- Ernest Cox, VP, Product Development
- Jamal Harris, Director, Customer Data
- Nina Locklear, Director, Procurement
- Adhira Patel, API Strategist
- Megan Pirato, Data Warehousing Specialist
- Rick Andersson, Manager, Data Governance
- Tessa Blackwell, Data Analyst
- Brianne Sand, Director, IT
- Shareefah Hakimi, Project Manager

## Dashboard Functionality
|Feature                  | Request                          |
|:------------------------|:---------------------------------|
|Create a new Dashboard| Dashoard should display trips based on lacation (starting and ending pointd)|
|Access | The users listed in the document will have access to the dashboard|
|Scope| Fields: userType, start_neighborhood, end_neighborhood, start_borough, end_borough, trip_minutes, Trip_count, zip_code_start, zip_code_end|
|Data Filters and Granularity | Filtered for month and season|             |

# Metrics and Charts
Tables for each graph/chart created

Chart 1
|Chart Feature | Requests                |
|:------------:|:------------------------|
|Chart Title | Start vs End Ride Location|
|Chart Type | Map |
|Dimensions| start and end locations|
|Metric| Number of rides|

Chart 2
|Chart Feature | Requests |
|:------------:|:------------------------|
|Chart Title | Popular Ride End Locations |
|Chart Type | Bar Graph |
| Dimensions | end neighborhood |
|Metric | Number of minutes, number of rides |

Chart 3
| Chart Feature | Requests |
|:------------:|:------------------------|
|Chart Title | Growth in Trips BY Month |
|Chart Type | Line Plot |
|Dimensions | Year, UserType |
| Metric | Number of rides |

Chart 4
| Chart Feature | Requests |
|:------------:|:------------------------|
| Chart Title | Number of Trips: Starting and Ending Locations |
| Chart Type | Bubble Chart |
|Dimensions | UserType, Start_neighborhood, End_neighborhood |
|Metric | Number of trips |

Chart 5 
|Chart Feature | Request |
|:------------:|:------------------------|
|Chart Title | Number of Rides vs Season |
|Chart Type | Bar Plot |
|Dimensions | Seasons, UserType |
| Metric | Number of rides |

### Project description

- What dataset you have chosen to work on:
https://github.com/fivethirtyeight/uber-tlc-foil-response

- What analysis/computation you plan to conduct: Uber files
- And why: to practice more with spark and dataframes
#### List of assignments
* Data cleaning and data wrangling (This includes dealing with missing values, converting datetimes (if needed) and for efficiency reasons creating one dataframe to save all csv files in each category below). [Naeim]
##### Tasks with Uber data (4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015)
1. Find highest pickup frequencies for month, day, hour (Work with Date/Time -> result with bar chart) [Azad ].
2. Find most pickup locations for Uber rides (Work with Lat & Lon) [Azad ].
3. Find popular companies in Taxi and Limousine Comission (TLC) list (Work with Base field) [David].
4. Find share of each company in each area, show the result on a map (Work with Folium) [David].
5. Work with file uber-raw-data-janjune-15.csv.zip to summerize all uber pickups (based on their Lat & Lon) in corresponding Borough (Visualize with Folium or bar chart) [David]
##### Tasks with For-Hire Vehicle (FHV) companies (10 files of raw data on pickups from 10 FHV companies. The trip information varies by company, but can include day of trip, time of trip, pickup location, driver's for-hire license number, and vehicle's for-hire license number.)
6. Find the most frequent address names from adress column for all companies (word count in strings) [Axel]
7. Find frequent times like the one in Uber section [Axel]
8. Find the most customer intensive neighborhoods for each company [Naeim]
9. Scalability tasks! [Naeim]
----- 
##### The approach you plan to takeproach
- Transformations , Filter, GroupBy … etc.
- Python , PySPARK , Jupyter notebook 
- For code, Github: https://github.com/daviddung1993/data_engineering1_project
- For repport, Overleaf: https://www.overleaf.com/project/621f656f061dadba9574e7e9 
- For scalability we’ll use dummy elements to check scalability or more datasets from: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

##### What technology will you work with, and how will you design your scalability studies?
- ?
##### Any preliminary results / deployments
- ?
##### Any risks you see and how you plan to mitigate those.
- Different files/branches for not overriding
- uber-raw-data-janjune-15.csv.zip has location id while the others have Lat,lon. 


#### Deadlines: 
- 14 March Code deadline (Task A, B) 
- 18 March Report Final report 
- 20 March Report hand in


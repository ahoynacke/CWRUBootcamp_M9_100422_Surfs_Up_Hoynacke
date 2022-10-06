# CWRUBootcamp_M9_100422_Surfs_Up_Hoynacke

## Background 
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Project Overview 
What You're Creating
This new assignment consists of two technical analysis deliverables and a written report. You will submit the following:

Deliverable 1: Determine the Summary Statistics for June
Deliverable 2: Determine the Summary Statistics for December
Deliverable 3: A written report for the statistical analysis (README.md)

## Deliverable 1 

1. A working query is written to retrieve the June temperatures from the date column of the Measurement table. 
<img width="698" alt="Screen Shot 2022-10-06 at 5 35 16 PM" src="https://user-images.githubusercontent.com/111096384/194422954-dcc787c7-2e93-49fe-956c-16cc1833fb8d.png">

2. The temperatures are added to a list & 3. The list of temperatures is converted to a Pandas DataFrame. 
<img width="718" alt="Screen Shot 2022-10-06 at 5 36 03 PM" src="https://user-images.githubusercontent.com/111096384/194423046-b752ca12-c6da-4e59-b4af-5c698e2c44e4.png">

4. Summary statistics are generated for the DataFrame. 
<img width="576" alt="Screen Shot 2022-10-06 at 5 37 12 PM" src="https://user-images.githubusercontent.com/111096384/194423225-bf257ead-30fc-4f85-a71f-076e3633c061.png">

## Deliverable 2 

1. A working query is written to retrieve the December temperatures from the date column of the Measurement table 
<img width="695" alt="Screen Shot 2022-10-06 at 5 38 09 PM" src="https://user-images.githubusercontent.com/111096384/194423316-02e6fdcd-1448-4763-9a78-461b4e9f7c91.png">

2. The temperatures are added to a list. & 3. The list of temperatures is converted to a Pandas DataFrame. 
<img width="732" alt="Screen Shot 2022-10-06 at 5 38 33 PM" src="https://user-images.githubusercontent.com/111096384/194423441-65df2032-f3a0-42e8-b2e7-8dc8bd0cc9ac.png">

4. Summary statistics are generated for the DataFrame. 
<img width="597" alt="Screen Shot 2022-10-06 at 5 39 38 PM" src="https://user-images.githubusercontent.com/111096384/194423573-518cd79f-5417-4d64-8246-d4ee8b44fe92.png">


## Deliverable 3 

### 1. Overview of the analysis: Explain the purpose of this analysis.
By using Python, Pandas and SQLAlchemy I filtered the date column with in the Measurements table in hawii.sqlite database to return all temperatures for the month of June. Once the filtered data was return I converted the data into lists (temperature lists) and then created Dataframes for those lists. Once the DataFrames were created I was able to pull summary statistics of the data. 

### 2. Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
By converting the data into lists and Dataframes I was ultimately able to retrieve the data statistics. 

June Temperature Stats:

<img width="123" alt="Screen Shot 2022-10-06 at 5 44 47 PM" src="https://user-images.githubusercontent.com/111096384/194424354-baea7436-ce0c-4056-976f-08175979c203.png">

December Temperature Stats: 

<img width="122" alt="Screen Shot 2022-10-06 at 5 46 04 PM" src="https://user-images.githubusercontent.com/111096384/194424566-b913ef7b-706c-42e6-8893-c8d7e73ac63d.png">

- The standard deviation for June is 3.25 and December is 3.75. There is a .5 difference between summer and winter seasons. 
- The min in June is 64 while the min in December is 56. The max in June is 85 and the max in December is 83. There is a 12 degree difference between the mins while there is only a 2 degree difference in the maxs. This shows that while both seasons had similar maxs December has a much lower min. 
- The averages were very similar - only showing about a 2 degree difference but that does no necessarily give an accurate dipication on the data because as outlines above December has a much colder min that June. 


### 3. Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
The data provides Avery with statistical analysis between June and December. This will help him decided is a year round bussiness is a good choice. 
In addtion to the queries created I would also look at percipitation and wind. This would help give a better picture on weather conditions and which areas would be the best to have a successful bussiness 

# Road-Accident-Visualization

This project involved the creation of dashboard from a road accident dataset. This was done by using the Pivot table feature in Microsoft Excel.
[Dataset download](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbVJmQUF5YVZQcGNraVdLVk00dkxaZGJ6QkxJUXxBQ3Jtc0tuMDJaQ2ZYeVBVNndJMFU3ZUNTbTFtaGVZOTJmcjYzcnNpZGxvblphczZldjRFRWJXT3FKNm9WY2xmazFVdF95THlCR3ZOdnp5VG9KSmtTSTVGYVhpNDVWMy1iV3I5dHhkOE1jYlhMQmVnNlJYWlRWbw&q=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2F1R_uaoZL18nRbqC_MULVne90h3SdRbAyn%2Fedit%3Fusp%3Dsharing%26ouid%3D116890999875311477003%26rtpof%3Dtrue%26sd%3Dtrue&v=XeWfLNe3moM)

## Key Performance Indicators(KPI's)
### Primary KPI’s
Total Casualties after accident with respect to accident severity and type of vehicle

### Secondary KPI’s
Total Casualties with respect to vehicle type
Maximum casualties by road type
Distribution of casualties by road surface
Relation between casualties by area/ location & Day/Night
Monthly trend showing comparison of casualties for current year and previous year


## Step 1 Data Cleaning
* Remove any rows with blank fields
* Checked for fields with similar meaning and merge them as under one field.
* Checked for spelling errors and correct them. In this case “Fatal” was incorrectly spelled as “Fetal”. All fields containing “Fetal” were changed to “Fatal” using excel find and replace.
* Months column was added using “Accident Date” column for better analysis.
* “Year” field was created Accident Date” column for better analysis. 


# Step 2 Total casualties
Table was created for total number of casualties by their severity.

<img width="266" alt="Total casualties" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/55ad3695-56fd-481a-8ac2-a78f2ebe89e2">

Pie charts were created using each severity.

<img width="841" alt="pie chart serverity" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/ad10a4bd-5bb0-42db-b282-f003d51cf61a">


# Step 3 
Table was created based on vehicle types in accidents
Similar fields have been merged together
“Car” and “Taxi/Private hire car” were merged into “Cars”
“Bus or coach” and “Minibus” were merged into “Bus”
“Van/Goods” and “Goods” related fields were merged into “Van”
All motorcycle related fields merged into “Bike”
All remaining fields were merged into “Others” as they are too low individually.

<img width="278" alt="vehicle type" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/89f9e280-7042-4918-a86a-95ea7759c5f2">

Car casualties are the most common accidents. A pie chart was created to illustrate this

<img width="613" alt="Car Casualties" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/76c11cdb-1aad-4635-b997-bd9f52a618c7">


# Step 4
Accident tables by month and a line chart are created relative to months in 2021 and 2022 to visually compare and show their differences

<img width="1048" alt="2021-2022" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/29327fa8-4e49-4aaf-ab96-dfe36d8cc724">

# Step 5
An accident table created with respect to road type is created and used to create a bar chart.

<img width="730" alt="road type" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/7b1c5972-06ac-44cd-9b43-e46e6097e971">

# Step 6
An accident table and treemap are created with respect to road surface is created and used to create a bar chart.
Similar fields have been merged together
“Flood” and “wet or damp ” were merged into “Wet”
“Frost or ice” and “Snow ” were merged into “Snow/ice”

<img width="551" alt="road surface" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/5f0d66db-f68b-4b6a-ba3f-b51c16338ee3">

# Step 7
Donut charts are created with regards to Urban and Rural and Light condition
Similar fields have been merged together
All darkness fields were merged into “Dark”

<img width="598" alt="url" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/e60b0427-d477-4039-b43e-2eb3c4c4a938">


# Step 8
A timeline was created to filter based on month and year

<img width="317" alt="timeline" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/0a9b7116-ede8-4d77-a733-9fab6f3e3a7a">

A Slicer was created to filter based on Urban and Rural locations

<img width="226" alt="u and r" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/5aaa5443-d1ef-4ac6-85d3-491ca23d33f0">


# Step 9
The last step is to put together all components taht have been created to form the dashboard

<img width="1102" alt="Sashboard" src="https://github.com/coldflows/Road-Accident-Visualization/assets/17550445/ac22c3ee-f407-47df-89c1-6a58f4c7ddf8">



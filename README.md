# A Review of Crime Data from Cleveland Police January 2024 to February 2025 

## Executive Summary 
![Service](assets/service_2.png) 
This project collates Cleveland Police crime data from January 2024 to February 2025 and looks at the probability of. 
This will assist with helping retail organisations to make decisions about Security resourcing and investment in training relating to managing threats and retail crime.

## Data Reprocessing
The data used for this project was sourceed from Police.uk/data. A site for open data about crime and policing in England, Wales, and Northern Ireland. This dataset was selected as it provides street-level crime in a clear and simple CSV format, the data is sorted by police force and neighborhood teams and classifies the type of crime. This makes it suitable for exploration of crime probability.   

## Loading and Initial Exploration 
The first stage was to import the CSV datasets into a Pandas Dataframe using the pd.read_csv () function. 
Basic exploration was completed using the df_adjustment.head function to understand the content and usability of the dataset. 

[Include screenshot]

## Data Selection
In order to focus on the objective of the project, it was important to select only relevant columns, in this instance 'Crime ID', 'Month', 'Longitude', 'Latitude', 'LSOA name', and 'Crime Type'.

[Include screenshot]


# MIST4610-Group-Project-2
# Team 8

### Team Name:

61608 Group 8

## Team Members:

[Will Solomon](https://github.com/Willtsolomon)

[Libby Lausier](https://github.com/libbylausier)

[Jack Smith](https://github.com/jacklsmith14)

[Grace Yao](https://github.com/graceyao2)

[Jack Clark](https://github.com/JackClark12)

[Zoey Cho](https://github.com/hc29584)


## Describing our dataset
Describing your dataset and what data it contains:
Where was it obtained, what are the dimensions of it (rows and columns), what are the various
columns, data types, etc. Describe it in sufficient detail so that an uninformed reader would
understand the dataset

We obtained our data from the city of New York's public database and the New York Department of Labor. 
We used two datasets. One was on shootings by Boro. The second contains information about unemployment rates in Brooklyn.

The Columns for the shooting data are:

- Incident Key: (INCIDENT_KEY) A unique identifier for each shooting incident.
- Occur Date: (OCCUR_DATE) The date when the shooting occurred (in the format MM/DD/YYYY).
- Occur Time: (OCCUR_TIME) The time when the shooting occurred (in the format HH:MM:SS).
- Borough: (BORO) The borough where the shooting occurred (e.g., Bronx, Brooklyn, Queens, etc.).
- Location of Occurrence Description: (LOC_OF_OCCUR_DESC) Description of the location of the shooting.
- Precinct: (PRECINCT) The precinct where the shooting occurred.
- Jurisdiction Code: (JURISDICTION_CODE) Code indicating the jurisdiction.
- Location Classification Description: (LOC_CLASSFCTN_DESC) Description of the location classification.
- Location Description: (LOCATION_DESC) Description of the specific location.
- Statistical Murder Flag: (STATISTICAL_MURDER_FLAG) A boolean indicating whether the shooting resulted in a murder (true/false).
- Perpetrator Age Group: (PERP_AGE_GROUP) Age group of the perpetrator.
- Perpetrator Sex: (PERP_SEX) Gender of the perpetrator.
- Perpetrator Race: (PERP_RACE) Race of the perpetrator.
- Victim Age Group: (VIC_AGE_GROUP) Age group of the victim.
- Victim Sex: (VIC_SEX) Gender of the victim.
- Victim Race: (VIC_RACE) Race of the victim.
- X Coordinate: (X_COORD_CD) X-coordinate of the location where the shooting occurred.
- Y Coordinate: (Y_COORD_CD) Y-coordinate of the location where the shooting occurred.
- Latitude: (Latitude) Latitude of the location where the shooting occurred.
- Longitude: (Longitude) Longitude of the location where the shooting occurred.
- Logitute and Latitude: (Lon_Lat) Combined longitude and latitude coordinates.

The Columns for the unemployment data are:

- Area
- Date (MM/YYYY) 
- Labor Force
- Employed
- Unemployed
- Unemployment Rate








## Questions
 1. Which Borough in New York City has had the most shootings from 2019 to 2022?
    Relevance: This question can be applied in many different scenarios. For one, policymakers can target specific areas in New York City that have the highest number of shootings to make a larger impact with the same amount of resources and effort. In addition, the data could be used in socio-economic research where researchers want to use shootings as a factor of educational, economic, and social status to determine which areas are lacking in one of the three categories and therefore could receive more aid from the government or local agencies.
    
 2. In Brooklyn, is there a correlation between the unemployment rate and number of shootings from 2019 to 2022?
    Our group prompted the correlation in the city of Brooklyn because it has the highest number of shootings of all other cities represented in the data during the timeframe from 2019 to 2022. Any correlation identified between the unemployment rate and a number of shootings could be essential information for the government in determining reasons for potential changes in unemployment rates in Brooklyn. In addition, if shootings were found to be correlated to the unemployment rate, it could be an area for policymakers to focus on in efforts to lower unemployment rates in the future.
    
## Manipulations

1. There was an issue where there was a person who was 1022 years old. This was a mistake in the data so it was excluded. 

2. There were 9 entries of null data where information was unavailable. These entries were filtered out in Tableau so it would of affect our results.
   
3. In the second question, we filtered the data for Only the borough of Brooklyn.

4. The date was filtered from 2019-2022.

 ## Analysis and Results 

 Analyze and visualize the results of your analysis and describe the implications of your analysis.
Please provide any citations if required as well as supporting visualizations and analysis
generated from Tableau

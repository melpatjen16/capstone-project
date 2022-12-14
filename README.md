# capstone-project

## Segment 1 Deliverables

### Topic

Selected topic - Relationship Between Criminal Behavior, Court Outcomes, and Regional Demographics

Reason why they selected their topic - Team members are interested in identifying patterns of behavior and fallacies about criminal outcomes. 

### Source of Data
Kaggle - [https://www.kaggle.com/code/nihandincer/data-analysis-of-boston-crimes](https://www.kaggle.com/datasets/AnalyzeBoston/crimes-in-boston)

Questions they hope to answer with the data: Is there a relationship between criminal behavior, regional demographics, and court outcomes within major metropolitan regions throughout the US. 

### S3 Link [https://bostoncrime.s3.amazonaws.com/archive1/crime.csv](https://bostoncrime.s3.amazonaws.com/archive1/crime.csv)

## Notes 
MJ - 11/7/Notes

Examine criminal justice system. 
Consider implications of behavioral health. 

Is there a relationship between criminal convictions and behavior for offenses occurring in areas of Virginia? 

Are there patterns regarding the following variables: 
 * Location
 * Race/Ethnicity; Gender
 * Economic variables (median household income, unemployment rate)
 * Homelessness or Mental Health indices 
 * Demographics of regional law enforcement. 

Narrowing down a topic. What problem/issue are we solving? Restricting it to VA gives us an easier start, place to find data. 
Contextualize crime statistics with demographic/behavior data/factors/variation within commonwealth
Behavioral data on juveniles vs. adults. Not as much on adults – how are these crimes then being classified? 
Violent crimes
Crimes against Person, Crimes against Property, and Crimes against Society
What’s considered a crime vs. offense or incident is not mutually exclusive. Contextualize
Conviction rates in the commonwealth; what stems it
Conviction rates with behaviors vs convictions rates with ethnic background and location; correlation with behaviors
Chances of winning a trial — based on judges; political parties/groups; economic status/class; age, demographic; religion; locality; types of crimes
Concrete crime factors?
1. Attitudes of policies of courts, prosecutors, and corrections 1. Locality 2. Density of population 3. Economic conditions 4. Employment 5. Cultural factors 6. Family 7. Weather 8. Police jurisdictions 9. Crime reporting and other tendencies 
veterans?
How to quantify
Compare/filter out these see where it leads 
Year to year?
Contextualize crime statistics with conviction rates in Virginia to highlight the behavioral, location, and demographic(ethnic background) factors…
Nonviolent conviction rates in VA – 
*1 Finishing up EDA process (exploratory data analysis)*
What are the features and relationships between them.
Variables: Case (#, code/ID, date), location (lat/long), charge, 
Provides guidelines for essential variables and removing non-essential variables
Identify outliers
Maximize insights of dataset

2 Create a working machine learning model — supervised learning model?? Labels vs no labels
Figure out the model to help figure out how to store it

Data & APIs:

https://statchatva.org/2020/09/14/crime-and-police-data-in-virginia/ (police and crime in VA)
https://www.opendatanetwork.com/entity/1600000US5167000/Richmond_VA/crime.fbi_ucr.count?crime_type=Aggravated%20assault&year=2018 (Richmond)
https://www.programmableweb.com/api/henrico-county-public-crime-data-access-rpc-api (henrico)
https://www.programmableweb.com/api/18f-crime-data (crime data explorer)
https://crime-data-explorer.fr.cloud.gov/pages/docApi 


# Segment 2 and 3 Deliverables

### Description of the data exploration phase of the project 

The team selected three cities to examine and establish if there was some trend by city or overall (all cities combined).


The datasets were combined using Pandas. The final set of cities included Boston, MA; Los Angeles, CA
; and Baltimore, MD

<img width="235" alt="Screenshot 2022-12-06 at 9 56 17 PM" src="https://user-images.githubusercontent.com/107972848/206083950-cbfca2fc-4c26-4cdc-8b16-f93de297f94d.png">

### Description of the analysis phase of the project


<img width="453" alt="Screenshot 2022-12-06 at 9 52 47 PM" src="https://user-images.githubusercontent.com/107972848/206084049-c6ffc649-a3d9-4ac6-a76f-0d92ba8c21f6.png">



![Screen Shot 2022-12-06 at 10 58 55 PM](https://user-images.githubusercontent.com/107972848/206084892-8df83766-e7e0-4e4c-8697-55a16fbd2db3.png)


### Libraries Used for Data Cleaning

<img width="886" alt="Screenshot 2022-12-06 at 9 40 27 PM" src="https://user-images.githubusercontent.com/107972848/206084193-7b6981b3-8458-409f-904f-a58bbe80712c.png">


### Draft Outline of Dashboard

Top Crimes
Crimes by Year, Mont
Crimes by Location (Latitude, Longitude)
Crime by Area (Maps)
Crimes by City by Year

### Dashboards Generated using Tableau 

OVERALL

https://public.tableau.com/app/profile/melanie.p.jenkins/viz/Overall_Story/CrimeTrendsbyCity?publish=yes

BALTIMORE

https://public.tableau.com/app/profile/melanie.p.jenkins/viz/Baltimore_Story_16704464678820/BaltimoreStory?publish=yes

BOSTON

https://public.tableau.com/app/profile/melanie.p.jenkins/viz/Boston_Story_16704464162940/BostonStory?publish=yes

LOS ANGELES

https://public.tableau.com/app/profile/melanie.p.jenkins/viz/Los_Angeles_Story/LosAngelesStory?publish=yes



### Presentation

https://docs.google.com/presentation/d/12QTT5_4vi3EK-5QgBurxKq9lYarOOCQJ0PierT--78g/edit#slide=id.g1abfe861f5f_0_25

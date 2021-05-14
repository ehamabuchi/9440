# NYPD Placement Strategization
- author(s): Jason Chong, Ellis Hamabuchi
- date created: 05/14/2021
- class: CIS 9440

Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications

Project Tools:
The tools used to build this Data Warehouse were: (change this to make applicable to your project)
1. For data integration - python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau

## Kimball Lifecycle Project Stages

### Project Planning

Motivation for project:
In 2020, the FBI reported 7,314 hate crimes in 2019 - the highest number since 2008. Since the beginning of the COVID-19 pandemic, as of April 2021, there have been almost 4,000 hate incidents taking place against Asian Americans and Pacific Islanders. Since this is an important topic that has hit home for both of us, we decided to look into hate crime, arrest, and 911 Calls data to determine where most crime stake place. With this analysis, we aimed to figure out where more NYPD officers should be stationed to mitigate the risk of crime occurring again.


Description of the issues or opportunities the project will address:
We should be able to use data visualization on hate crime, arrest, and 911 calls data to figure out what precincts or boroughs have the highest concentration of crimes, as well as what the bias motive descriptions are to figure out where more NYPD officers should be stationed.

Project Business or Organization Value:
The NYPD can better allocate police resources to minimize crimes and increase their return on investment. Resources saved by effectively stationing police officers can then be used for other programs or for investing in tools that might support the NYPD further.

Data Sources:
1. Hate Crimes: https://data.cityofnewyork.us/Public-Safety/NYPD-Hate-Crimes/bqiq-cu78/data
2. NYPD Calls for Service: https://data.cityofnewyork.us/Public-Safety/NYPD-Calls-for-Service/n2zq-pubd
3. NYPD Arrests: https://data.cityofnewyork.us/Public-Safety/NYPD-Arrest-Data-Year-to-Date-/uip8-fykc

### Business Requirements Definition

List of Data Warehouse KPI's:
1. Number of hate crimes by borough
2. Number of hate crimes by precinct
3. Arrests by precinct
4. Arrests per month
5. 911 calls by precinct


### Dimensional Model

This project's Dimensional Model consists of (x) Facts and (y) Dimensions

Use correct file path here to show picture of dimensional model...
![Alt text](/img/dimensional_model.jpg)

This project's Kimball Bus Matrix:

Use correct file path here to show picture of Kimball Bus Matrix...
![Alt text](/img/kimball_bus_matrix.jpg)

### Business Intelligence Design and Development

List of Visualizations for each KPI:
1. Bar Chart for comparison of hate crimes and corresponding bias motive descriptions across boroughs 
2. Packed Bubble Chart for easy identification of precincts where highest count of hate crimes took place
3. Tree map to determine the makeup of arrests by precinct and borough
4. Line chart for time series analysis of the number of arrests over the year of 2020
5. Tree map to determine the makeup of calls across precincts and boroughs

BI Application Wireframe design:

![Alt text](/img/wireframe_design.jpg)

Picture of final Dashboard:

Use correct file path here to show picture of Dashboard...
![Alt text](/img/Dashboard.jpg)

### Deployment

The project was deployed on Tableau Public:
Hate Crimes: https://public.tableau.com/profile/jason.chong4422#!/vizhome/Dashboard1_16204413917470/HateCrimes
Borough/Precinct Data: https://public.tableau.com/profile/jason.chong4422#!/vizhome/FinalDashboard_16207919631870/BoroughPrecinctData?publish=yes
Arrests: https://public.tableau.com/profile/jason.chong4422#!/vizhome/FinalDashboard_16207919631870/Arrests2020?publish=yes

 

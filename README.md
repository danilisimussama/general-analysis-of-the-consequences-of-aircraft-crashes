## Analysis of the consequences of aircraft crashes
### Purpose of the study
The purpose of the project is to assess the distribution of fatalities by aircraft category and to compare key metrics between these categories. The results are presented in tables and graphs.
### Methodology and structure of the analysis
- The analysis was performed separately for two periods: before 18 September 2001 and after that date.
- Three categories of flights are considered: civil, cargo, and military. 
- Only aviation accidents are included in the analysis, not aviation incidents
**Note:** differences in absolute losses are partly explained by exposure (number of flights and passengers). 
### Definitions
- An **aviation accident** is an event related to the flight operation of an aircraft in aviation that has resulted in the death or serious injury of any person(s), significant damage to or loss of that aircraft.
- An **aviation incident** is an event associated with the use of an aircraft (from boarding to disembarking) caused by deviations from normal operation that created or could have created a safety hazard but did **not** result in an aviation accident (catastrophe or crash). This is an incident caused by technical failures or crew errors.
### Key findings
- Comparison of periods and categoriesIn the 20th century, only 19 out of 100 aircraft involved in civil aviation accidents resulted in no casualties. 
- In the 21st century, despite significant safety innovations, the probability that all people on board survive an aviation accident has increased by only 3%.
- Nevertheless, the number of casualties of half or more of all people on board still represents a 78.20862% probability in the event of an aviation accident in the 21st century. This is 0.55983% lover than in the last century.

> left chart: 1908-2001, right chart: 2001-2019

<p float="left">
  <img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/PDF%20-%20Comparison%2020.jpg" width="45%" />
  <img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/PDF%20-%20Comparison%2021.jpg" width="45%" />
</p>
<p><img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/PDF%20-%20Summary%20Tables%20all.jpg" width="70%" /> </p>

### Interpretation of Summary Tables
To better understand the patterns shown in the graphs, summary tables were compiled for the entire observation period and grouped by flight type

### Cargo Flights
The data clearly indicates that cargo aircraft accounted for 1,719 fatalities out of 2,080 people involved in accidents.
This disproportion is explained by the consistently small number of people on board: on average, cargo flights carry no more than 5 individuals, of whom 3 are crew members.
Because of this low occupancy, even a single fatal accident significantly shifts the overall fatality ratio.

### Military Flights
For military aviation, the available data is limited to officially published statistics.
Despite this limitation, the trend is unambiguous: in the event of an aviation accident, the probability of fatality reaches approximately 94%.
This extremely high rate reflects both the operational specifics of military flights and the severity of incidents that are officially recorded

> Summary statistics 1908-2019

<p><img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/PDF%20-%20Summary%20Statistics%20all.jpg" width="70%" /> </p>

## Flight Numbers and Safety Trends

Estimating the total number of commercial flights in the early decades of aviation is difficult due to the absence of complete historical records. However, available data suggests that between 1908 and 2000, there were approximately 300–400 million commercial flights.
In the 21st century, the scale of global aviation increased dramatically. Between 2004 and 2019, the world recorded 495 million commercial flights, including 38.9 million flights in 2019 alone. This growth highlights a key trend: modern aviation safety is driven primarily by preventing accidents altogether rather than mitigating their consequences.
Based on these flight volumes, the estimated probability of being involved in an aviation accident in the 21st century is approximately 0.0000896%. 
For context, this is significantly lower than:
- the probability of being struck by lightning (0.006%),
- or the probability of a fatal shark encounter (0.00003%).
These comparisons illustrate how exceptionally rare aviation accidents have become relative to other low‑probability events.

>The number of commercial flights (millions) by year

<p><img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/2004-2019.png" width="70%" /> </p>

## Conclusions
The aviation industry has become significantly safer over time, primarily due to improvements that prevent accidents from occurring in the first place. However, when accidents do happen, their consequences remain severe—especially for crew members and for military flights.
This contrast highlights both the increased confidence in aviation safety and the effectiveness of modern safety measures, given the extremely low number of aviation accidents relative to the total number of flights

### Data Visualization
The document includes visualizations that illustrate:
- the distribution of fatality probabilities across different aircraft categories,
- the year‑by‑year dynamics of the number of commercial flights.
In addition, summary tables present aggregated data on fatalities, injuries, and fatality probabilities for each flight category

### Repository structure

- data/ — initial data (CSV)
- images/ — images for readme
- sas/ — SAS project
- reports/html/ — HTML‑reports (SAS output)
- reports/pdf/ — PDF-reports (SAS output)
- README.md — this file

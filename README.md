## Analysis of the consequences of aircraft crashes
### Purpose of the study
The purpose of the project is to assess the distribution of fatalities and injuries by aircraft category and to compare key metrics between these categories. The results are presented in tables and graphs.
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
<p><img src="https://github.com/danilisimussama/general-analysis-of-the-consequences-of-aircraft-crashes/blob/main/images/PDF%20-%20Summary%20Tables%20all.jpg" width="90%" /> </p>

## Overview
Датасет содержит сведения о падениях самолётов за весь доступный период наблюдений.  
Включены три категории: **Cargo**, **Cilvilian**, **Military**. Для каждого инцидента доступны поля: `date`, `aircraft_category`, `aboard`, `aboard_passengers`, `aboard_crew`, `fatalities`, `fatalities_passengers`, `fatalities_crew`, `ground`, `death_probability` и др.

## Key findings
- **Доля по категориям:** Civilian ≈ **84.7%**, Military ≈ **14.0%**, Cargo ≈ **1.35%**.  
- **Средняя вероятность смерти (по категории):** Military ≈ **0.94**, Cargo ≈ **0.89**, Civilian ≈ **0.79**.  
- **Среднее число людей на борту:** Civilian ≈ **34**, Military ≈ **29**, Cargo ≈ **5**.  
- **Вывод:** гражданских инцидентов больше в абсолютных числах из‑за гораздо большей экспозиции (больше полётов/рейсов); при этом риск на один инцидент выше у военных и грузовых самолётов.  
- **Time split:** данные разделены на периоды **до 18.09.2001** и **после 18.09.2001** для оценки влияния событий 2001 года на частоту и смертность.

## Repository structure

- data/ — initial data (CSV)
- images/ — images for readme
- sas/ — SAS project
- reports/html/ — HTML‑reports (SAS output)
- reports/pdf/ — PDF-reports (SAS output)
- README.md — this file


> **Примечание:** пути указаны относительно корня репозитория — при необходимости поправьте имена файлов.


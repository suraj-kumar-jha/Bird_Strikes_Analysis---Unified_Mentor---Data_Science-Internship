## Bird_Strikes_Analysis -- [Transportation and Communication Project]
------------------------------------
Associated with Unified Mentor Private Limited

### Tools Used:-
------------------------------------

Tableau: For data visualization and interactive dashboards.

MS Excel: For data cleaning and analysis.

MS Word: For documenting findings and creating reports.

### TABLE OF CONTENTS:-
------------------------------------

- [KPI’S REQUIREMENT](#kpi's-requirement)
- [CHARTS REQUIREMENT](#charts-requirement)
- [DASHBOARD 1](#dashboard-1)
- [DASHBOARD 2](#dashboard-2)
- [CONCLUSION](#conclusion)
- [WAYS TO REDUCE WILDLIFE STRIKE PROBLEMS](#ways-to-reduce-wildlife-strike-Problems)

------------------------------------
### PROBLEM STATEMENT:-
------------------------------------

As transportation and urbanization surge, so do concerns about environmental impact and safety. 
Bird strikes pose a serious threat to aircraft safety, particularly during critical flight phases. 
By analyzing FAA data on bird strikes (2000-2011) and leveraging advanced technologies like Multi-Agent Systems (MAS), 
we aim to devise innovative solutions to enhance aviation safety and sustainability.

------------------------------------
### KPI’S REQUIREMENT
------------------------------------

#### 1. Total Airports:
The total number of airports included in the analysis.
Provides an overview of the geographical scope of the study and the diversity of airport environments considered.

#### 2. Total Aircraft:
The total number of aircraft involved in reported bird strike incidents. Indicates the frequency and extent of bird strike incidents
across different aircraft types, aiding in risk assessment and mitigation strategies.

#### 3. Total Damage Aircrafts:
The total number of aircraft that sustained damage due to bird strikes. 
Highlights the impact of bird strikes on aircraft safety and operational costs, guiding preventive measures and resource allocation.

#### 4. Total Damage Cost:
The total cost incurred as a result of aircraft damage from bird strikes. Quantifies the financial implications of bird strikes on the
aviation industry, informing cost-benefit analyses and investment decisions in safety measures.

#### 5. Total People Injured:
The total number of individuals injured as a result of bird strike incidents.
Reflects the human toll of bird strikes, underscoring the importance of mitigating these incidents to protect passenger and crew safety.

#### 6. Total Wildlife Strikes:
The total number of reported wildlife strikes, including bird strikes and strikes involving other wildlife such as bats or ground animals.
Provides a comprehensive view of the broader wildlife strike phenomenon, informing holistic strategies for wildlife hazard management at airports.

<img width="639" alt="Screenshot 2024-05-22 at 12 24 47 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/312036ab-bb64-4f51-9fe9-eb757e492562">

------------------------------------
### CHARTS REQUIREMENT
------------------------------------

#### 1. Year vs Total Wildlife Strikes:
=> Analysis of the total number of wildlife strikes reported each year. Insights into trends and patterns in wildlife strike occurrences over time, 
aiding in long-term risk assessment and mitigation planning.

<img width="628" alt="Screenshot 2024-05-22 at 12 26 26 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/491f79bc-4a43-4346-8f71-b1c75c48e0d8">


o The years 2009 and 2010 experienced the highest number of wildlife strikes, indicating periods of heightened risk to aircraft safety.

o Conversely, the years 2000 and 2004 saw the lowest number of wildlife strikes, suggesting potential areas of success in mitigation efforts during those periods.

------------------------------------

#### 2. Year vs Total Damage Cost:
=> Examination of the total cost incurred due to aircraft damage from wildlife strikes each year.
Provides insight into the financial impact of wildlife strikes on the aviation industry, guiding investment decisions in safety measures
and infrastructure improvements.

<img width="626" alt="Screenshot 2024-05-22 at 12 27 44 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/a3e3736c-a5dc-45f7-991d-8c6a0bface84">

o The years 2001 and 2006 recorded the highest total damage costs resulting from wildlife strikes, highlighting significant financial implications for the aviation industry during those years.

o Conversely, the year 2000 had the lowest total damage cost, indicating a potential correlation between wildlife strike frequency and associated costs.

------------------------------------

#### 3. Month vs Total Wildlife Strikes:
=> Evaluation of the total number of wildlife strikes reported each month. Identification of seasonal variations and peak periods of wildlife strike
incidents, informing operational planning and resource allocation.

<img width="637" alt="Screenshot 2024-05-22 at 12 28 36 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/cf49cc2e-c734-4dd4-9742-16b07962a50f">

o Wildlife strikes were most prevalent from July to October, emphasizing the importance of heightened vigilance and mitigation efforts during these months.

o Conversely, the period from January to June experienced the lowest number of wildlife strikes, suggesting potential seasonal patterns in wildlife activity and aircraft interactions.

------------------------------------

#### 4. Month vs Total Damage Cost:
=> Assessment of the total cost incurred due to aircraft damage from wildlife strikes each month.
Helps identify months with higher financial losses due to wildlife strikes, facilitating targeted interventions and risk management strategies.

<img width="641" alt="Screenshot 2024-05-22 at 12 29 27 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/eaacd0f9-5d96-40d6-89dd-90e3f73476d0">

o The months of January and October recorded the highest total damage costs from wildlife strikes, underscoring the need for targeted interventions during these periods.

o Conversely, September had the lowest total damage cost, indicating potential opportunities for effective risk mitigation strategies.

------------------------------------

#### 5. Top 10 US Aircraft vs Total Wildlife Strikes:
=> Analysis of the top 10 aircraft models involved in wildlife strike incidents in the US.
Provides insights into aircraft vulnerability to wildlife strikes, guiding aircraft design improvements and operational procedures.

<img width="612" alt="Screenshot 2024-05-22 at 12 30 29 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/d2c8d4a9-e755-4355-8d93-0e5b522bd197">

o Aircraft models CL-RJ100/200 and B-737-300 experienced the highest number of wildlife strikes, highlighting vulnerabilities that warrant further investigation and mitigation measures.

o Conversely, aircraft models MD-82 and MD-80 had the lowest number of wildlife strikes, suggesting potential areas of success in aircraft design or operational procedures.

------------------------------------

#### 6. Top 10 US Airports vs Total Wildlife Strikes:
=> Examination of the top 10 airports with the highest number of reported wildlife strikes in the US.
Helps identify high-risk airport environments and prioritize wildlife hazard management efforts and infrastructure enhancements.

<img width="597" alt="Screenshot 2024-05-22 at 12 32 13 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/88e54d61-44db-42a6-bccb-debb3354f460">

o Dallas/Fort Worth International Airport reported the highest number of wildlife strikes, indicating a need for targeted wildlife management strategies in high-risk airport environments.

o Conversely, Baltimore/Washington International Airport had the lowest number of wildlife strikes, suggesting effective wildlife management practices or environmental conditions conducive to reduced wildlife interactions.

------------------------------------

#### 7. Phase of Flights vs Wildlife Strikes:
=> Analysis of the phase of flight (e.g., takeoff, climb, approach, landing) during which wildlife strikes occur.
Helps identify critical phases of flight with higher likelihoods of wildlife strikes, guiding operational procedures and risk mitigation strategies.

<img width="531" alt="Screenshot 2024-05-22 at 12 34 27 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/fa3eb189-8cc3-493a-b6d2-7dab5e9775c0">

o Wildlife strikes were most frequent during the approach phase of flight, highlighting the critical importance of vigilance and mitigation measures during this stage.

o Conversely, wildlife strikes were least frequent during descent, suggesting potential opportunities for risk mitigation strategies targeting specific flight phases.

------------------------------------

#### 8. Pilot Warned vs Total Wildlife Strikes:
=> Evaluation of the number of wildlife strikes reported when pilots were warned about wildlife presence.
Provides insights into the effectiveness of pilot warnings in preventing wildlife strikes and informs decision-making regarding wildlife managementstrategies.

<img width="501" alt="Screenshot 2024-05-22 at 12 35 25 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/54d6692d-45d1-444f-bd27-be957f9f560b">


o The chart indicates a fairly balanced distribution between wildlife strikes where pilots were warned versus those where they were not. Approximately 46.4% (31,860) of the wildlife strikes occurred after pilots were warned, while 53.6% (36,789) happened without prior warning.

o Despite efforts to warn pilots, a significant portion of wildlife strikes (more than half) still occurred without any prior warning, highlighting the challenge of effectively predicting and communicating potential wildlife hazards to pilots.

------------------------------------

#### 9. Altitude vs Total Strikes:
=> Examination of the altitude at which wildlife strikes occur. Helps identify altitude ranges with higher risks of wildlife strikes, 
guiding airspace management and flight planning.

<img width="603" alt="Screenshot 2024-05-22 at 12 36 19 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/32c52e6c-7efc-41a8-980f-6b091229b430">


o Wildlife strikes were significantly more common at altitudes below 1000 feet, indicating heightened risk during take-off and landing phases.

o Conversely, the frequency of wildlife strikes decreased at altitudes above 1000 feet, suggesting potential altitude-based mitigation strategies.

------------------------------------

### Dashboard 1

<img width="643" alt="Screenshot 2024-05-22 at 12 37 21 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/6e2fc2b3-237f-400a-b951-535b801241e7">

------------------------------------

### Dashboard 2

<img width="640" alt="Screenshot 2024-05-22 at 12 38 47 AM" src="https://github.com/suraj-kumar-jha/Bird_Strikes_Analysis---Unified_Mentor---Data_Science-Internship/assets/155900363/8db8fdf9-6d1f-437a-8234-b3a8443f2989">

------------------------------------

### Conclusion
------------------------------------

#### § Peak wildlife strike years: 2009-2010; Lowest occurrences: 2000, 2004.

#### § Years with highest damage costs: 2001, 2006; Lowest costs: 2000.

#### § Seasonal trends: Peak strikes July-October; Lowest January-June.

#### § Months with highest damage costs: January, October; Lowest: September.

#### § Aircraft models most prone: CL-RJ100/200, B-737-300; Least: MD-82, MD-80.

#### § Airport with highest strikes: Dallas/Fort Worth; Lowest: Baltimore/Washington.

#### § Critical flight phases: Most strikes during approach; Least during descent.

#### § Altitude risk: More strikes below 1000 feet; Fewer above 1000 feet.

------------------------------------
### Ways to Reduce Wildlife Strike Problems
------------------------------------

#### 1. Implement Wildlife Management Programs:
=> Create comprehensive programs to control wildlife populations and modify habitats around
airports.

#### 2. Enhance Airport Infrastructure:
=> Improve airport infrastructure to deter wildlife and minimize bird strike hazards.

#### 3. Conduct Wildlife Hazard Assessments:
=> Regularly assess wildlife hazards to prioritize mitigation efforts and allocate resources
effectively.

#### 4. Improve Pilot Training and Awareness:
=> Provide pilots with training on bird strike avoidance techniques and increase awareness about
reporting procedures.

#### 5. Enhance Reporting and Data Analysis:
=> Encourage reporting of wildlife strikes and analyze data to identify trends and implement
targeted mitigation strategies.

#### 6. Develop Innovative Technologies:
=> Invest in technologies such as bird detection radar and acoustic deterrents to reduce the risk of bird

#### 7. Collaborate with Stakeholders:
=> Work with airport operators, airlines, regulators, and wildlife experts to develop holistic approaches to
wildlife strike mitigation.

#### 8. Public Education and Outreach:
=> Increase public awareness about bird strike risks and promote responsible behavior near airports to
minimize wildlife attractants.

----------------------******************------------------------

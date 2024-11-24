# -Analysis-on-Safest-Aircrafts-to-Purchase

**Business Understanding**
Objective- The goal of this project is to advise the management that is venturing into new business of Purchasing Aircrafts for Commercial and Private use by enterprises on aircrafts they can consider to purchase.
In my analysis, I will help management understand the potential risks of the aircraft business if they are to venture into it.
**Focus Areas:**
1.Identifying low-risk aircraft for purchase.
2.Understanding potential risks in the aviation industry.


**Data Understanding**
➢I worked on the Aviation Dataset, provided by NTSB Aviation Accident Database (1962–2023).
➢The data contained historical information on :
oAccidents-(Accident.Number)
oLevel of injuries- (Total Fatal injuries, Total Serious injuries, Total Minor injuries, and Total 
Uninjured)
oAircraft details- (Aircraft make, aircraft model etc)
➢The data was useful as it helped in doing analysis on risk and safety trends of the various
aircrafts

**Data Preparation**
❖When preparing data, it was important to do some data cleaning, to prepare the data for 
analysis.
❖Checks Made:
1) Missing Values- When checking for missing values, Column “Schedule” had the most missing 
values , hence decided to drop this entire column, also since it will not help in our analysis at this 
stage.
2)Replaced other missing values with zeros(0) to better perform statistical measures eg. Mean, 
median etc
3) Added a new column “ Total Injuries” by summing all injuries levels, to better help with 
analysis

**Data Analysis**
I used basic statistical measures in my analysis, i.e
•Correlation- .corr()- This was so as to find the relationship between different Variables
•Findings: There was low correlation between ‘No of Engines’ compared to different Level of 
Injuries.
**Metrics For Analysis**
The Key metrics I applied for analysis was to Understand:
1. Trend of the Aircraft Accidents over time
2. Identify which aircraft models/make have the highest fatalities 
**Key Findings**
❖Trends on Aircraft Accidents- It was found that the number of accidents kept reducing over the 
years
❖Findings on the Models/Make with the highest fatalities: Analysis showed some carriers, like 
Malaysian Airlines System and Ethiopian Airlines, have higher fatality rates, suggesting more risk 
if the organization decides to purchase these.
• Also some aircraft makes, like Boeing, show a higher number of uninjured passengers, indicating 
better overall safety .

**Recommendations**
❖From the analysis, I would recommend that management :
❖Avoid aircraft from high risk carriers such as ‘Malaysian Airlines System, that reported highest 
number of fatalities and injuries
❖Consider other metrics such as number of uninjured passengers as part of analysis to better 
help in their decisions.
Next Steps
❖Management can consider expanding to the Airline Business as from the Trend seen, there has 
been constant decline in number of flight accidents and this may be due to increase in 
technology, and better current standards to regulate the air industry.
❖They can also seek services of a flight consultant to assess further technical risks when it 
comes to aviation, technology to decide the make to go for if purchase is ever a question.

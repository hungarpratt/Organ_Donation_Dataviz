# Organ Donation in the United States: An Interactive Data Visualization Project

Project Summary
---
As a living kidney donor, I became interested in the broader ecosystem of organ donation in the United States. While living donation plays a role, the overwhelming majority of organ transplants (including kidneys, hearts, and lungs) rely on organs from deceased donors. As a result, state organ donor registries—most commonly accessed through Departments of Motor Vehicles—are critically important to the functioning of the system.
This project examines how demographic characteristics and personal beliefs differ among Americans who have registered as organ donors or have express edwillingness but have not yet registered, and those who have affirmatively chosen not to donate. Using national survey data, the analysis explores which factors are most strongly associated with donor willingness, recognizing that the most recent available data for this survey are from 2019.

Data Source
---
Data for this project come from the 2019 National Survey of Organ Donation Attitudes and Practices (NSODAP), published by the U.S. Department of Health and Human Services’ Health Resources and Services Administration (HRSA). The survey includes responses from approximately 10,000 U.S. adults, collected via telephone and online questionnaires, and captures demographic characteristics, donor registration status, donation willingness, and a range of belief-based measures related to organ donation.

Data Preparation
---
Prior to analysis, the data were cleaned and recoded to support both statistical analysis and data visualization. Two methodological decisions are particularly important to note:
- Donation inclination categorization: Rather than comparing registered donors to all other respondents, I created a composite category labeled “Willing,” which includes both registered donors and respondents who were not registered but reported being “strongly” or “somewhat” willing to donate their organs. This group was compared to an “Unwilling” category, consisting of respondents who were not registered and who expressed “somewhat” or “strongly” negative views toward donation.
- Handling of belief nonresponses. For analyses involving belief statements, respondents who declined to answer a given question were excluded from that specific analysis. If nonresponse reflects social desirability concerns or reluctance to express unpopular views, this approach may introduce a degree of response bias and should be considered when interpreting results.

Creating Charts in Observable Plot
---
In preparation for importing the relevant data into Observable, I needed to calculate dozens of perctentages using lookup formulas and then organized subsets of  the data into different tables (see all the tabs after *Data* in the donating.csv file). 

Here is a listing of my two live Observable Notebook dashboards which contains links to all the individual files:
- Demographics and beliefs dashboard (bar charts and radar charts): https://observablehq.com/d/09a64a089c52ecd1
- Maps dashboard (maps): https://observablehq.com/d/17187e69979a7b0f 

Contact
---
If you have any questions or would like to discuss further, feel free to contact me, Harley Ungar, at harley.ungar@gmail.com.


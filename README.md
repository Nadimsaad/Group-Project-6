# Group-Project-6

Description of the dashboard and each widget 
(what you want to show, why the particular chart is chosen), calculations 

AVERAGE TIME FOR TRANSACTION :
•	Stating last Year’s i.e. ‘2021’ average time (in days) of all transactions (left side)
•	Current Month-to-date average time status (in days) (right side)

CHARGES BY PERIOD :
•	Stating last Year’s i.e. ‘2021’ total paid charges i.e.’2021’ (Left side)
•	Current Month status (Right side)  

STATUS OF PAYMENT in a colored treemap:
We chose a treemap because the size of each quadrant is shaped by the total values
Calculation: we looked at the counts for each status type (New, completed, pending, delivered, etc.) and 
their corresponding amounts in USD

PAYMENT STATUS FORECAST (BY QUARTER) in a circle views chart:
A circle view is a good representation to see the counts of each transaction type on quarterly basis  
Calculation: we placed the sum of inital amounts in rows and a forecast indicator, status group, Year and quarter in the columns for New, Ongoing and completed transactions

ISSUES IN CORRESPONDENCE CHAIN in a colored pie chart:
A pie chart allows us to have a clear idea of the % of the status of the following transaction types (Pending, Processing, and Cancelled) 
Calculation: we counted each transaction type and divided it by the total to obtain the %

PROBABILITY OF DELAY BY DESTINATION COUNTRY in a horizontal bar chart:
We chose a colored horizontal bar chart to visualize best the time scale of the current delays per beneficiaries banks
Calculation: we calculated the BIC for each bank in a country (in rows) and the Aggregated probility of delay (columns) to obtain the percentages

TROUBLES FORECASTS (chart TBD):
We were not able to complete this forecast thus couldn't define a chart type
Calculation: we imagined using the Total counts of the following transaction types (Pending, Processing, and Cancelled) 

DURATION/ PER COUNTRY MAP   
Seeing the countries on world map so that the user can click of the country of his choice to have a idea of the duration for a transaction to take place
Calculation: we place the generated latitude (in rows) and the generated longitude (in columns) and placed the BIC countries and average durations in Marks Ability to choose a destination country on the map 

Trello: https://trello.com/b/swG8a7zL/project-6-group-3

Tableau online: https://prod-uk-a.online.tableau.com/#/site/ironzijing/workbooks/95937/views


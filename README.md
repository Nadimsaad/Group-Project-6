# Group-Project-6

Project 6 | Descriptive, predictive analysis and visualization in Tableau

Content

Introduction
Project Goal
Requirements
Necessary Deliverables
Presentation
Suggested Ways to Get Started
Introduction

This project aims to practice in descriptive and prescriptive statistics and dashboards creation with Tableau.

Project Goal

The goals of this project is to develop the dashboard in Tableau. The dashboard should reflect the descriptive and predictive analysis of data and explain the state of the payments.

Requirements

We are going to use Trello for the project management. This time you will need to indicate there not only the names of the tasks but tasks description also.
The domain is related to the crossborder payments, please read the recommended sourses to get knowledge about the subject.
Examine the dataset for the possible issues
Develop the system of Key Performance Indicators (or the system of widgets that should be shown). Please keep in mind the must-have answers:
Average time for transaction
Status of payment
Total charges per period
Payment status forecast
Issues in correspondence chain
Probability of delay
Troubles forecast
Develop the idea of your dashboard:
what exactly you want to show?
what should be the layout?
which widgets represent the most powerful insights?
Your dashboard should give the possibility to filter the data
Please note, that you need to have at least 12 widgets that describe your data.
Please note, you have at least 3 widgets that should reflect forecasted values.
Describe the idea of the dashboard and each widget (what you want to show, why the particular chart is chosen), calculations in the readme file.
After your dashboard is ready, please, create a presentation.
Non-functional requirements:

Use the corporate colors of the product
Add logo of the product
Add the SWIFT compatible label Please check the website https://paylocator.com/ for having mentioned detailes.
Necessary Deliverables 

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


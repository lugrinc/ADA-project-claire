# ADA_Project
Influence of demographics and economics in the Swiss votations of the last years.

## Abstract

Swiss people are asked to vote for different law proposals each year. These proposals called « votations » cover a wide range of subjects. 
In this project the outcomes of the votations (participation rate, percent in favor) will be analysed regarding their thematic category and the political party that emited it. The relation between these results and demographics, economics and education level of each canton will be analyzed.

The goals of this project are :
<li>To create an interactive map, showing the results of the votation per can and per thematic category (votation about economics, immigration, education…) 
<li>To show statistical evidence that some denographics parameters could explain part of the votation outcome

## Data Description
Most of the data used in this Project can be downloaded from the online portal of the Swiss government. https://www.admin.ch/ We will mainly use demographic and political data for the different cantons.

POLITICAL DATA
<li> Results of the federal votations (2010-2016) 
For each popular votation, we have the number and percentage of people that voted yes, no or blank, as well as the participation levels. This information is available for the whole [country](https://www.bfs.admin.ch/bfs/fr/home/statistiques/politique/votations.assetdetail.255285.html) (downloadable table) or by [canton]( https://www.bfs.admin.ch/bfs/fr/home/statistiques/catalogues-banques-donnees/tableaux.html) (tables to be scraped)
<li> [Votations recommentations]( https://www.bfs.admin.ch/bfs/fr/home/statistiques/politique.assetdetail.335646.html) by party (2010-2016)
For each votation in a given year, we have the recommendations of the main parties (as yes or no).

DEMOGRAPHIC DATA
<li> [Education level](https://www.bfs.admin.ch/bfs/fr/home/statistiques/education-science/niveau-formation-competences.assetdetail.333136.html) by canton (2014)
For each canton, we have the absolute number and percentage of resident people having achieved each of the following educational levels: sans formation postobligatoire, degré secondaire professionnel, degré secondaire general, formation proffessionnelle supérieure, hautes écoles.
<li> [Education expenses](http://www.scris.vd.ch/Default.aspx?DocID=5468&DomId=2021) by canton (2005-2012)
For each canton, amount of money (and percentage of total expenses in the canton) that was invested in education. The amount of money spent per habitant is also available.
<li> [Age and sex]( https://www.bfs.admin.ch/bfs/en/home/statistics/population.assetdetail.291230.html)  by canton (2014)
Basic demographic data by canton such as number of people by gender and age categories. 

## Feasibility and risks

## Deliverables

We will produce an interactive map of the swiss cantons.
The user will be able to choose a demographic parameter (age, sex, average wage, education level..) and it will be displayed on the map as a background color for each canton. Then the used will be able to choose to add on the map the outcome of the votations (all votations together or a thematic). The outcome could be displayed as bullets representing the % of yes and the % of no for the category of votation. Each canton would have 2 bullets (yes and no) of size proportional to the outcome of the vote. The bullets color could correspond to the color of the political party that proposed (yes bullet) or opposed (no) the votation
We will keep only the demographics for which we found a significant impact on the outcome.

## Time Plan


Timeplan:

1.	Data Wrangling : Get the data, clean them. Make a table with all the informations per canton. Make a second table with the outcomes of the votations per cantons.
Deadline : 21st November

2.	Statistical analysis : find relevant relations between the demographics and the votation outcome.
Deadline : 5 Decembre

3.	Visusalisation : Build the interactive map(s).
Deadline : 20 Janvier


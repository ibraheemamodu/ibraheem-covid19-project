# Project Name: Global Covid-19 Analysis

# Problem Statement

Corona Virus (Covid-19) is a global pendemic which started in 2019 and rapidly spread through the world which led to a global lockdown, it is therefore, critical to know how much damage it has caused the world. Hence this project.

# Data Sourcing

The data used for this project was scraped from https://aka.ms/30DLCOVID19GitHubData into Microsoft Excel where the Analysis was done

# Data Cleaning and Transformation

Data was cleaned and transformed in Power Query so as to receive live updates on the datasets. The following transformations was done:
Changed query names to confirmed; death; and recorvered accordingly, made first row as column header, unpivot other columns with State/Province, Country/Region, Long, and Lat selected. Data types were changed, columns renamed (confirmed, death, and recovered). Merged queries (confirmed and death) as new (Merge 1) then, merged the third query (recovered) to Merge 1 and renamed it ConsolidatedData after this the data was loaded back into Microsoft Excel and then analyzed.


# Findings

1. United States has the highest confirmed cases with  28,199,334,543 as at June 20th 2022 while North Korea has the lowest with just 36 cases.
2. Among the top 5 countries with the highest death United States has the highest death ( 432,252,388), followed by Brazil, India, Mexico, and, Russia accordingly
3. India has the highest recorvered cases.
![Cocid dashb  2](https://user-images.githubusercontent.com/107144786/175726732-b2e856e3-611b-4dbd-b950-2b4c9e8a4992.JPG)

# Reccomendation

United States should take the necessary steps to stop/reduce the spread of the virus.

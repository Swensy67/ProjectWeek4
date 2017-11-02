# Introduction

-------------------------------------------------

# Presentation of data

The file "summarySCC_PM25.rds" contains 6 497 651 obs. of 6 variables. You can find their signification
in the following array : 

Variable Name                       | Explanation                     | Value 
----------------------------------- | ------------------------------- | -------------:
fips                                | US County                       | five-digit number (represented as a string)                     
SCC                                 | Source of pollution             | digit string
Pollutant                           | Measurement of PM25             | string
Emissions                           | alount of PM2.5 emitted         | tons
Type                                | type of source                  | NON-ROAD, NONPOINT, ON-ROAD and POINT
Year                                | Year of emission recorded       | 1999, 2002, 2005 and 2008

------------------------------------------------

The file "Source_Classification_Code.rds" contains 11 717 obs. of 15 variables. You can find their signification
in the following array : 

Variable Name                       | Explanation                     | Value 
----------------------------------- | ------------------------------- | -------------:
SCC                                 | Source of pollution             | From 10100101 to 2260001030 
SCC                                 | Source of pollution             | digit string
Short.Name                          | Number of the volunteer         | From 1 to 30
EI.Sector                           | Number of the volunteer         | From 1 to 30
Option.Group                        | Number of the volunteer         | From 1 to 30
Option.Set                          | Number of the volunteer         | From 1 to 30
SCC.Level.One                       | Number of the volunteer         | From 1 to 30
SCC.Level.Two                       | Number of the volunteer         | From 1 to 30
SCC.Level.Three                     | Number of the volunteer         | From 1 to 30
SCC.Level.Four                      | Number of the volunteer         | From 1 to 30
Map.To                              | Number of the volunteer         | From 1 to 30
Last.Inventory.Year                 | Number of the volunteer         | From 1 to 30
Created_Date                        | Number of the volunteer         | From 1 to 30
Usage.Notes                         | Number of the volunteer         | From 1 to 30

-----------------------------------------------------------

# Question 1

Have total emissions from PM2.5 decreased in the United States from 1999 to 2008? 
Using the base plotting system, make a plot showing the total PM2.5 emission from all 
sources for each of the years 1999, 2002, 2005, and 2008.

-----------------------------------------------------------

# Question 2

Have total emissions from PM2.5 decreased in the Baltimore City, Maryland (fips == "24510")
from 1999 to 2008? Use the base plotting system to make a plot answering this question.

-----------------------------------------------------------

# Question 3

Of the four types of sources indicated by the type (point, nonpoint, onroad, nonroad) 
variable, which of these four sources have seen decreases in emissions from 1999–2008 
for Baltimore City? Which have seen increases in emissions from 1999–2008? 
Use the ggplot2 plotting system to make a plot answer this question.

-----------------------------------------------------------

# Question 4

Across the United States, how have emissions from coal combustion-related sources changed 
from 1999–2008?

-----------------------------------------------------------

# Question 5

How have emissions from motor vehicle sources changed from 1999–2008 in Baltimore City?

-----------------------------------------------------------

# Question 6

Compare emissions from motor vehicle sources in Baltimore City with emissions from motor 
vehicle sources in Los Angeles County, California (fips == "06037"). 
Which city has seen greater changes over time in motor vehicle emissions?
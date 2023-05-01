# Covid-19's Effect on the Great Smoky Mountains National Park

## Overview
The first recorded case of Covid-19 in the United States was discovered on January 20, 2020. On March 15, 2020, states began implementing lockdowns to help slow the spread.
 
As a result of these lockdowns our most visited National Park, the Great Smoky Mountains (GRSM), saw dramatically reduced visitation. This has provided the rare opportunity to see how reduced visitation impacts the local area, both environmentally and economically.


## Motivation
As an avid hiker, landscape photographer, and naturalist, analyzing the effects of COVID-19 on a national park is valuable for gaining insights into how reduced visitation can impact natural environments and local communities.

National parks are vital areas for conservation and recreation, and changes in visitation patterns can have significant environmental and economic implications. Understanding this impact could help identify ways to manage these areas in the future, while balancing the need for conservation and tourism.
  

## Data Question
The Great Smoky Mountains National Park has introduced new daily parking passes to help raise additional funds for the park and reduce the amount of traffic through the park. Is there evidence to support that this reduced traffic will have an environmental effect?  How was the local economy and job market affected?  

### MVP Questions:
1.	How was park visitation affected and how has it recovered?

2.	How was air and water quality trending before, during and after the Covid-19 pandemic?

3.	How has the outdoor recreation job market been affected? 

4.  What impact can be seen on the economy of the local area? 

5.  How have trends continued since lockdowns have ceased?

### Stretch:
1.  What other factors contribute to environmental recovery? 

2.  What is the approximate dollar amount lost due to Covid-19 in the Tennessee area of the park?

## Minimum Viable Product (MVP)
-   PowerPoint presentation examining the findings.
-   Tableau Dashboard showing changes over time.

## Schedule
1.	Get the Data - (4/11/23)
2.	Clean & Explore the Data - (4/20/23)
3.	Internal demos - (4/21/23)
4.	Create presentation of your analysis - (4/25/23)
-   Powerpoint presentation
-   Tableau dashboard
5.	Demo Day - (4/28/23)

## Data Sources
-	[Environmental Protection Agency](https://aqs.epa.gov/)
    Historical Air Quality Index data

-	[Tennessee Department of Environment & Conservation](https://dataviewers.tdec.tn.gov/ )
    Pigeon River water parameters

-	[National Park Service](https://irma.nps.gov/Stats/)
    Visitation Statistics for Great Smoky Mountains National Park

-   [Bureau of Economic Analysis](https://apps.bea.gov/)
    Contributions to percent change in real GDP and Outdoors Recreation Satelite Accout

-   [Water Quality Calculator](https://www.rowanmccarthy.com/blog/)
    Excel Based National Sanitation Foundation Water Quality Index Calculator (WQI)

-   [GRSM Boundary](https://grsm-nps.opendata.arcgis.com/datasets/nps::grsm-boundary/explore?)

-   [TN counties](https://hub.arcgis.com/datasets/myUTK::tiger-line-2018-tennessee-counties/explore?location=36.135420%2C-83.816221%2C6.98)

-   [Pigeon River Coordinates](https://geography.brucemyers.com/rivers/view/14905/GeoJSON)   

## Known Issues and Challenges
-	Acquiring data from a variety of sources.

-	Understanding water quality parameters and how WQI is calculated.
    Reformatting data to better work with WQI Calculator.

-	Moving data effectively between Excel/Python/Tableau.

-   Creating a GeoJson of the pigeon river from found coordinates.

## Technology
-   Python - Pandas, Seaborn, Datetime, RegEx, Matplotlib
-   Github - Version Control
-   Excel - WQI Calculation, Data Transformation
-   Powerpoint - Presentation
-   Tableau - Dashboard
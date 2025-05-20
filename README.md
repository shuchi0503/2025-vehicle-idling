# Dip in Idling Cases after Congestion Pricing

This data journalism project investigates chnages in vehicle idling patterns in Manhattan in relation to the congestion zone that went into effect in Janurary 2025. 

## Byline 

**By** Shuchi Shah

**Date:** May 20, 2025

## Sources

This project uses to two data sets from NYC Open Data:
- [311 Complaints] (https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)
  This is a data set of all idling complaints and service requests made in New York City by calling 311.
  
- [idling DEP- OATH Hearings Division Case Status] (https://data.cityofnewyork.us/City-Government/idling-DEP/4agj-k4jv/about_data)
  This is a data set of alleged vehicle idling violations that go through the city's administrative law court- the NYC Office of Administrative    Trials and Hearings (OATH). In other words, these are summons/Notices of Violations of alleged idling violations from OATH.

### Categories  

-311

For the purpose of this project, I filtered the data set to get results for complaints regarding vehicle idling from Jan 1, 2015 to May 5, 2025. This is the data set I downloaded and did my analysis on.

It includes the date (Created Date), brief description (Descriptor), location and vehicle type of each complaint. It contains a few different kinds of location data such as zip codes, latitudes and longitudes, cross streets, street names, violaton address etc. For my analysis, I used columns - Cross Street 1 and Cross Street 2. I chose these with the aim of mapping idling patterns as accurately as possible. 

-OATH
I filtered the data set to get results for summons regarding vehicle idling from Jan 1, 2015 to May 5, 2025. This is the data set I downloaded and did my analysis on.

It includes date, location as well as information about the respondent, hearing details and penalty amounts. This data set also contains multiple kinds of location data such as borough, block, lot, zip codes and street names. This time, I chose zip codes instead of street names due to messy data in the latter column (many have incomplete infomration and have formatting errors).  

### Parameters

-311

I looked at idling complaints from 60th to 90th street, to see any changes in number of complaints closest to the congestion zone and then as we go further away from it. Since the congestion zone was a major aspect of the analysis, I chose not to include streets further north of 90th street.  
  
-OATH

I analysed zip codes that roughly cover the areas between 60th and 90th street, to be as accurately comparable to the 311 analysis as possible.

### Analysis

Compared complaints/summons from January to April for each year from 2015 to 2025. I chose these months to account for lack of data for 2025. Otherwise, I would be comparing 12 months of each year to 4 months of 2025 which would not be an accurate analysis. This anayslis can be reproduced at the end of 2025 for all 12 months. 

Write a little more in detail about stripes etc.


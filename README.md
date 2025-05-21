# Dip in Idling Cases after Congestion Pricing

This data journalism project investigates changes in vehicle idling patterns in Manhattan in relation to the congestion zone that went into effect in Janurary 2025. 

## Byline 

**By:** Shuchi Shah

**Date:** May 20, 2025

## Sources

This project uses to two data sets from NYC Open Data:
- [311 Complaints] (https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)
  This is a data set of all idling complaints and service requests made in New York City by calling 311.
  
- [idling DEP- OATH Hearings Division Case Status] (https://data.cityofnewyork.us/City-Government/idling-DEP/4agj-k4jv/about_data)
  This is a data set of alleged vehicle idling violations that go through the city's administrative law court- the NYC Office of Administrative    Trials and Hearings (OATH). In other words, these are summons/Notices of Violations of alleged idling violations from OATH.

### Categories  

- 311

For the purpose of this project, I filtered the data set to get results for complaints regarding vehicle idling from Jan 1, 2015 to May 5, 2025. This is the data set I downloaded and did my analysis on.

It includes the date (Created Date), brief description (Descriptor), location and vehicle type of each complaint. It contains a few different kinds of location data such as zip codes, latitudes and longitudes, cross streets, street names, violaton address etc. For my analysis, I used columns - Cross Street 1 and Cross Street 2. I chose these with the aim of mapping idling patterns as accurately as possible. 

- OATH
 
I filtered the data set to get results for summons regarding vehicle idling from Jan 1, 2015 to May 5, 2025. This is the data set I downloaded and did my analysis on.

It includes date, location as well as information about the respondent, hearing details and penalty amounts. This data set also contains multiple kinds of location data such as borough, block, lot, zip codes and street names. This time, I chose zip codes instead of street names due to messy data in the latter column (many have incomplete infomration and have formatting errors).  

### Parameters

- 311

I looked at idling complaints from 60th to 90th street, to see any changes in number of complaints closest to the congestion zone and then as we go further away from it. Since the congestion zone was a major aspect of the analysis, I chose not to include streets further north of 90th street.  
  
- OATH

I analysed zip codes that roughly cover the areas between 60th and 90th street, to be as accurately comparable to the 311 analysis as possible. I used [this UPS map] to refer to zip codes- (https://www.unitedstateszipcodes.org/)  

### Analysis

Compared complaints/summons from January to April for each year from 2015 to 2025. I chose these months to account for lack of data for 2025. Otherwise, I would be comparing 12 months of each year to 4 months of 2025 which would not be an accurate analysis. This anayslis can be reproduced at the end of 2025 for all 12 months. 

With the 311 complaint data, I divided the area above the congestion zone, 60th to 90th street into stripes like 60th-65th streets, 66-70th streets, 71st-75th streets, 76th-80th streets and finally 80th-90th streets. 

### Judgement Calls and Caveats

I chose to analize the last ten years. There was data available for years prior to that but I felt a decade was a good amount to see any patterns. 

In addition to the source quoted in the story, I spoke to a sustainbility expert who is also working with idling complaint data. He did not want to be named or quoted directly int he story. What he shared with me was helped me understand the administrative process better and so I chose to include it in the story without naming him. 

It takes a few months for idling complaints to be processed and issued a summons or a notice of violation. It is thus likely that the updated data if checked after a few months or at the end of 2025, will have complaints even in the Jan-April period. It would be important to do a follow-up story, potentially with more voices, if the findings still stand in a year's time. 

The 311 complaint data for the specific geographic region and timeline I was analyzing, has very few data points. However, I still chose to include it because it is still a popular and important resource/grievance method for New Yorkers. 

I also spoke to a couple of people who work in the this area but chose not to include direct quotes in the story because I felt they did not add much to the narrative, although it helped for my reporting and understanding of the topic.

### Limitations

The story does not include complaint data from the Citizen Air Complaint Program. This data is not publicly available. I have FOILed for this data but in the mean time found and worked with these alternative data sources. 

The DEP spokesperson could not confirm, deny or comment definitively on whether idling complaints have decreased after congestion pricing went into effect. 


### Additional Resources 

[Github Repo](https://github.com/shuchi0503/2025-vehicle-idling)





# IBM-Capstone-Project

***Introduction:*** The people of New Yorker use the 311 system to report complaints about the non-emergency problems to local authorities. Various agencies in New York are assigned these problems. The Department of Housing Preservation and Development of New York City is the agency that processes 311 complaints that are related to housing and buildings.

In the last few years, the number of 311 complaints coming to the Department of Housing Preservation and Development has increased significantly. Although these complaints are not necessarily urgent, the large volume of complaints and the sudden increase is impacting the overall efficiency of operations of the agency.

***Goal:*** The Department of Housing Preservation and Development has approached your organization to help them manage the large volume of 311 complaints they are receiving every year.

***Cap-Stone project Questions:*** The agency needs answers to several questions. The answers to those questions must be supported by data and analytics. These are their  questions:

***Problem statement:***

***Question 1:*** Which type of complaint should the Department of Housing Preservation and Development of New York City focus on first?¶ Strategy: There are many different categories of housing problems, one can focus on the category which has maximum complaints. This will help managment to better manage the resources.

***Question 2:*** Should the Department of Housing Preservation and Development of New York City focus on any particular set of boroughs, ZIP codes, or street (where the complaints are severe) for the specific type of complaints you identified in response to Question 1?

***Question 3:*** Does the Complaint Type that you identified in response to Question 1 have an obvious relationship with any particular characteristic or characteristic of the Houses?

***Datasets:*** You will use two datasets from the Department of Housing Preservation and Development of New York City to address their problems.
311 complaint dataset

This dataset is available at https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9. You can download part of this data by using SODA API.

Download only the data that is related to the Department of Housing Preservation and Development. Also, restrict your data to the limited number of fields. Otherwise, your data size will be unnecessarily large, and it might not work in the Watson Studio environment. Too much data can also be very slow to process and analyze.

PLUTO dataset for housing

This dataset for housing can be accessed from https://data.cityofnewyork.us/City-Government/Primary-Land-Use-Tax-Lot-Output-PLUTO-/xuk2-nczf. After you download the data, use only the part that is specific to the borough that you are interested in based on your analysis.

***Conclusions for the Problem Statement:***

***Concluding Question1:*** Based on the plot it is clear that maximum number of complaints are coming from HEAT/HOT water category. So HPD should address the HEAT/HOT WATER complaint first. The problem remains all time high. It is clear with the time dependent plots.

***Concluding Question2:*** The analysis shows the severly affected boroughs with the HEATING complaints. In addition we show the number of complaints in histogram visulization.Furthermore, to make the use of zip code I have used street view map and clusters to represent the problem affected area more concisely. This map is interactive and hence gives managers to spot immidiatley the top complaints areas.

***Concluding Question3:*** Using Pearson correlation techniques predicts that 'BldgDepth', 'ResiFAR', 'NumFloors', 'ZipCode' are the important features. Furthermore, Random Forest method gives'BldgArea', 'BldgDepth', 'BuiltFAR', 'Lot', 'LotArea', 'ResArea', 'YearBuilt', 'ZipCode' as an important features. The accuracy score shows that using these important features have 87% accuracy. By using these two methods we are confident that out model is good enough to use for prediction for out of sample data and detect the correct housing characterstics that are highly correlated to complaint type.

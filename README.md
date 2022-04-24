Purpose and Overview 

The purpose of this analysis is to provide the client, a ride-share application company, information to help improve access to ride-sharing services and to determine affordability for its services in under-served areas.   The data looks at three main target areas: urban cities, suburban cities, and rural cities. It comprises date, time, city, number of drivers, and logs of the individual rides for each city type.  This analysis focused on exploration and a broad review of trends in the data preliminary to recommendations for further action.

Data Set

The data set consists of two .csv files, ride_data.csv and city_data.csv.  City_data.csv acts as a key to the ride data, and contains the name of name, type, and number of drivers for every city included in the analysis.  The ride data is the record of every ride occurring in the study time frame, the first four months of 2019. There are 2,376 records in ride_data.csv.

Analysis

Analysis proceeded on a merged dataframe of the two .csv files to compare the three city types based on number of rides logged, the total amount of fares generated, and the average fare per driver and per ride. To visually show trends over time, the analysis includes a line graph displaying total rides by week by city type.  

Results 
Overall

•	The higher the population density, the higher the number of rides generated

•	The higher the number of rides per area, the lower the per-driver and per-ride average fare

•	Urban areas generate high-volume, low-fare ride-sharing

•	Rural areas generate low-volume, high-fare ride-sharing

•	Suburban areas complete the trend, placing between rural and urban areas in terms of rides generated and fares charged

Average Fare per Ride

•	Rural, suburban average fare per ride are higher than urban:

  o	39% higher average fare per ride than rural cities
  
  o	10% higher average fare per ride than suburban fares 
  
Number of Rides 

•	Urban areas generated 68% of total

•	Suburban 26%

•	Rural 5%

Average Fare per Driver

•	Rural average fare per driver ($55), 69% greater than urban ($17)

•	Suburban average fare per driver ($40), 42% greater than urban 

•	Urban areas generate largest number of rides with the lowest average fare per driver and per ride

Number of drivers

•	Urban areas had the greatest number of drivers, 81% of the total

•	Rural came in at around 2.6%, suburban at 16.5%

Timing (per week and per month)

•	Ride volume was evenly distributed month to month

•	The weekly graph shows some slight variation among the weeks; notably, January started low for all types; late February showed increases all three types, urban in particular

•	March through April showed an overall decline I the number of rides

•	These trends evened out over the longer month-to-month term

Summary

Overall, it seems clear that population density drives ride-sharing volume. Whether this is a function of concentrated urban lifestyle, or an outcome of reduced service levels resulting in reduced opportunity for customers in in outlying areas, cannot be determined from this analysis alone.  As a preliminary step, it does help define further action. The first step would be to refine the companiy’s objectives in terms of expanding and enhancing services.  Knowing and understanding the needs and wants of the different customer bases represented in the three types is important to the success of the company’s mission. What works for a densely populated urban area likely does not have the same cachet with a smaller, more sparsely populated one. Identifying those differences and building a business model to successfully address them is therefore the first order of business. 

My recommendation would be to develop and conduct studies building off the core of this analysis, including:

1.	Defining service areas in terms of geographical data and population density.  At this point, the three categories are very broad, and do not address defining characteristics of the different customer base.	
	
2.	Defining service areas in terms of region, such as state or metropolitan area. People select to live in urban, rural, or suburban areas as an expression of lifestyle preference.  Such preferences can dictate desire to use ride-sharing services and for different reasons.  Identifying these differences would allow the company to tailor its services to the individual areas.	
	
3.	Investigating the difference in per-ride fares among the three types to assess whether the difference is a result of time and duration or higher base charges.
	
4.	Collecting ride data that includes destination to build a customer-use profile.  There may be opportunities for the company to enter into partnerships with other transport service entities to expand and facilitate personal travel particularly in underserved areas.  It might also create opportunities for the company to expand its own offerings beyond its current model.
	 
5.	Better defining the customer base would help identify latent demand, correlating needs with services. 

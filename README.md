# Airbnb-NYC
### Dataset link : https://www.kaggle.com/datasets/thedevastator/airbnbs-nyc-overview
### Dashboard link : https://public.tableau.com/app/profile/reema.sk/viz/AIR-BNBNYC/Dashboard3

## Problem Statement

Analyze the Airbnb NYC dataset to derive actionable insights that can help hosts optimize their revenue and occupancy rates, as well as assist Airbnb in promoting listings in various boroughs. This involves understanding host performance, room type preferences, and geographical trends to provide strategic recommendations for both hosts and the platform.

By leveraging the insights given, hosts can improve their financial performance, and Airbnb can enhance its platform's overall attractiveness to both hosts and guests.


### Steps followed 

- Step 1 : Load data into Tableau, dataset is a csv file.
- Step 2 : Create a new calculated field to calculate occupancy rate and revenue. 
- Step 3 : The occupancy rate is calculated with [365-[availability_365])/365].
  ![image](https://github.com/ReemaSheikh/Airbnb-NYC/assets/171484655/e8d0af18-77b5-4d52-a0b5-31a061ff5b63)
  
- Step 4 : The revenue is calculated with [Booked days] into [Price].
  ![image](https://github.com/ReemaSheikh/Airbnb-NYC/assets/171484655/eeb51273-4e7c-48d3-84e7-9eb304f356d8)
  
- Step 5 : Multiple sheets are generated based on each chart type and the variables.
- Step 6 : The dashboard is generated by clicking on new dashboard.

# Snapshot of Dashboard (Tableau service)

![image](https://github.com/ReemaSheikh/Airbnb-NYC/assets/171484655/9f3637e8-0bd0-4e45-a9e8-e5782c99df7b)
 
 # Report Snapshot (Tableau public)

 ![image](https://github.com/ReemaSheikh/Airbnb-NYC/assets/171484655/b1a47070-f50e-4254-b7a3-e5db8a4c3644)

# Insights

A single page report was created on Tableau Desktop & it was then published to Tableau service.

Following inferences can be drawn from the dashboard;

### [1] Top host based on revenue:
The top host based on revenue is Sally

   Sally is the top host based on revenue, but not the one with the most listings. This likely means that Sally has a higher average daily rate (ADR) than other hosts. This could be because her listings are in Manhattan (which has the highest average price per night according to the image), entire homes/apartments (which tend to be more expensive than private rooms).
   
           Thus, the revenue generated by the host Sally is $10.19 million and has only 12 listings in entire homes/appartments. The average price listed is $3091.42.
           
### [2] Highest no. of listings based on room type:
The highest no. of listing based on room type is entire homes/apartments

This could be due to tourists or business travelers preferring more space and privacy than a private room offers.

    The entire homes/apartments is generating revenue of $1,256.33 million, which is highest among others and has 24.92k no. of listings accross NYC.
   
  
  ### [3] Highest no. of listing based on neighbourhood group:
  The highest no. of listing based on neighbourhood group is Manhattan

  Manhattan is the most popular borough in NYC for tourists, so it makes sense that it would have the most listings
  
      Manhattan has 21.10k no. of listings and is generating a revenue of $980.17 million.

 ### [4] Highest no. of listings based on host:
 The highest no. of listing based on host is Michael
 
 This doesn't necessarily mean he has the most revenue. It could be that he has a lot of listings in less expensive neighborhoods or room types (like private rooms).
 
         This is due to the average price listed and the and the room type. The average price listed by Sally is higher that that of Micheal which is at $160.42. Micheal has listed private room type which is not generating much revenue.
 
 ### [5] Highest occupancy rate based on neighbourhood group:
 The highest occupancy rate based on neighbourhood group is Manhattan
 
 Manhattan is the most popular borough in NYC for tourists, so it makes sense that it would have the most listings and the highest occupancy rate.

          Manhattan has listed more no. of room types in entire homes/appartments which is causing it to have highest occupancy rate.

# Recommendations

### For Hosts:
Sally: She could consider raising her rates slightly to see if she can increase her revenue even more.
Michael: Since he has a lot of listings, he could focus on optimizing his listings to improve their occupancy rate, especially by listing more in entire home apartment room type.

### For Airbnb:
Promote non-Manhattan listings: They could highlight listings in other boroughs to encourage tourists to explore different areas of NYC. This could help reduce pressure on Manhattan and spread the economic benefits of tourism more evenly.

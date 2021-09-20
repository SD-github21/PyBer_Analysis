# PyBer Analysis

## Overview of PyBer Analysis conducted on 2019 data
The purpose of the PyBer analysis was to compare ride-sharing data across diverse city types in order to identify existing disparities that can assist with key business decisions. Comparisons between urban, suburban, and rural city types were examined across several metrics to determine the affordability and accessibility of ride-sharing services amongst these key groups. 

## Resources
- Data Sources: city_data.csv & ride_data.csv
- Software: Python 3.7.10, Anaconda 1.7.2, Jupyter Notebook, Pandas, Matplotlib

## Results 

### The following table depicts a summary of important metrics about ride-sharing data across diverse city types:

![image](https://user-images.githubusercontent.com/85533099/133962344-d19c1e8c-2c83-44ea-9d92-e9e2acd90925.png)

  ### Summary of findings for suburban cities versus urban cities
  - The total number of rides over a four month period (January - April) for suburban cities was **2.60** times less than urban cities (625 versus 1,625 rides). 
  - The total number of drivers over a four month period (January - April) for suburban cities was **4.91** times less than urban cities (490 versus 2,405).
  - The revenue generated from the total sum of fares over a four month period (January - April) for suburban cities was **$20,498.05** less than urban cities ($19,356.33 
    versus $39,854.38).
  - The average fare per ride over a four month period (January - April) for suburban cities was **$6.44** higher than the average fare per ride for urban cities ($30.97 
    versus $24.53).
  - The average fare per driver over a four month period (January - April) for suburban cities was **$22.93** higher than the average fare per driver for urban cities ($39.50 
    versus $16.57).
    
     
  ### Summary of findings for rural cities versus urban cities
   - The total number of rides over a four month period (January - April) for rural cities was **13** times less than urban cities (125 versus 1,625 rides). 
   - The total number of drivers over a four month period (January - April) for rural cities was **30.83** times less than urban cities (78 versus 2,405).
   - The revenue generated from the total sum of fares over a four month period (January - April) for rural cities was **$35,526.45** less than urban cities ($4,327.93
      versus $39,854.38).
   - The average fare per ride over a four month period (January - April) for rural cities was **$10.09** higher than the average fare per ride for urban cities ($34.62 
      versus $24.53).      
   - The average fare per driver over a four month period (January - April) for rural cities was **$38.92** higher than the average fare per driver for urban cities ($55.49 
     versus $16.57).
    

### The following image depicts a multiple line chart revealing trends in revenue generated by city type across a four month period (January - April): 

![image](https://user-images.githubusercontent.com/85533099/133941160-22071ba6-a24f-4041-9c94-795561349caa.png)

### Summary of findings for suburban cities
   - The red line shows the total fares generated within suburban cities over a four month period (January - April). 
   - It appears that the end of the 3rd week of February generated the highest revenue for total fares, i.e., around $14,000 and this was a fairly dramatic increase.
   - Furthermore, there appears to be a trend showing that total fares decrease towards the end of the months of January through March. 
   - However, April seems to show an opposite trend, where the revenue experiences a sharp decline within the first week but then rises sharply thereafter. 
   - The revenue generated by suburban cities appears better than that for rural cities but substantially lower than the urban cities. 

### Summary of findings for rural cities
   - The blue line shows the total fares generated within rural cities over a four month period (January - April). 
   - It appears that the beginning of April generated the highest revenue for total fares, i.e., $500, while the 3rd week of February came close to $500, i.e., ~$450. 
   - There appear to be more steady fluctuations of rising and falling revenues across the 4 month period.
   - Unfortunately, overall, it is very clear that the revenue generated is hovering around the same level across the entire four month period, despite peaks and dips over 
     time and that amount is dramatically lower than suburban and urban cities. 

## Recommendations

According to the summary statistics comparing city types, urban cities generate the highest revenue when compared to rural and suburban cities. The multiple line chart provides a more detailed visualization of how urban cities generate the highest revenue when compared to rural and suburban cities across a 4 month period (January - April). Therefore, the results of this analysis illuminate the need for PyBer to focus more attention on suburban and rural cities. Findings clearly show that there are significant problems with the affordability of fares and the accessibility of drivers in rural and suburban cities. One hypothesis to explore would be to consider that this discrepancy is due to the significantly lower number of drivers in rural and suburban cities. Therefore, it is recommended that PyBer:

  - Target more funding towards increasing the number of drivers in rural cities for a 3 month trial period
  - Target more funding towards increasing the number of drivers in suburban cities for a 3 month trial period
  - Repeat the same summary statistics comparing rural, suburban, and urban cities across this 3 month trial period to determine whether this approach will generate increased 
    revenue 
  - Track total revenue between rural, suburban, and urban cities across this 3 month trial period using the same visualization process of a multiple line chart to determine     whether what was observed from January to April changes during summer months (June - August),  or fall/winter months (September - December). 


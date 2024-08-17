# Navigating-New-York-Airbnb-Market
Analyzing New York City's Airbnb market using listing data from 2019

In 2023, a Local Law placed restrictions and guidelines around short-term rentals. As a result, strict limitations were placed on Airbnb operations in the city. For the purpose of the analysis, listing activity in 2019 was used. The link to the dataset can be found here. The code for my analysis can be found here.  

In the analysis, I answer the following questions:
* Which Neighborhoods had the most rentals?
* What was the pricing distribution by room type across NYC?
* How many hosts had multiple properties?

## Neighbourhood Analysis
To begin, the dataset contained listing activity of 48,895 unique rental properties within the NYC region. Below, you can see the number of rentals by Neighborhood Group.  

![image](https://github.com/user-attachments/assets/e05a98f4-669f-4325-a0b0-94fda6b39c38)

Manhattan and Brooklyn had the most rental properties. In the notebook used for the analysis, you can also find an interactive map showcasing listings by region. The most interesting insights came from breaking these neighbourhood groups into smaller neighbourhoods. Woodside had the most rentals with 3920 in the neighborhood. The mean rental unit for each neighbourhood was 221, however, 75% of neighbourhoods (3rd Quartile) had 154 rental units or fewer.  

Upon investigating further it was found that 76% of total Airbnbs in NYC are concentrated in 14% of the neighborhoods. In other words, 76% of all Airbnbs in NYC were focused on only 30 neighbourhoods.

## Price Analysis
There are three types of rooms available on Airbnb: entire home/apartment, private room & shared room. The prices vary depending on the type of room which can be seen in the table below.  
![image](https://github.com/user-attachments/assets/8f19b1f8-e6a8-4871-b007-903880dd36ac)

The prices for rooms were most expensive in neighborhoods around and including Chelsea as can be seen in the geo-scatter plots below.  
![image](https://github.com/user-attachments/assets/ad76a813-26c9-4592-b344-e3ead7a67a1c)  
![image](https://github.com/user-attachments/assets/3f73cb2d-6b72-4065-91da-e88257c47a8a)  
![image](https://github.com/user-attachments/assets/45ed8eb9-3026-4916-adb9-7c66c1d60986)  

The average price per night in NYC is $152, compared with the mean price for a night in Chelsea which is $250.  

## Host Analysis
32,303 hosts only one property in NYC. However, roughly 40 hosts own more than 20 rental units each which account for 2205 rental units collectively. However, the most intriguing insight was that most of these hosts have their properties listed with a 30-day min stay.  
![image](https://github.com/user-attachments/assets/d911b19e-a066-4fd1-842d-f62b88af038a)


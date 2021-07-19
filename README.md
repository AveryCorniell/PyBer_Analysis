# PyBer Analysis  

## Analysis Overview  
The purpose of this analysis is to provide PyBer Ride Sharing company with an exploratory analysis  
on Drivers, Dates, and Fares of Cities based on City Types (Urban, Suburban, and Rural), in the forms  
of several different visualizations, that will help Pyber to improve access to ride sharing services,  
as well as, determine affordability for potentially underserved neighborhoods.  

## Resources and Process  
### Data Files:
- city_data.csv  
    - 3 columns (city, driver_count, type)    
    - 120 records  
- ride_data.csv    
    - 4 columns (city, date, fare, ride_id)    
    - 2375 records    
**(All imported data was clean and contained 4 months of rideshare data)**  

### Open-Source Coding Software:    
- Python       
- Pandas   
- Matplotlib (matplotlib library)    
- Statistics    
- Numpy    

### Deliverables:  

**NOTE:**    
- **Charts and graphs were plotted using both the MATLAB and Object-Oriented Approaches.**  
- **All charts were created uniformly with the following colors scheme:**    
- **coral for urban areas**    
- **skyblue for suburban areas**    
- **gold for rural areas**      
    
#### Bubble Chart  
- showcases the average fare versus the total number of rides with bubble size based on the  
  total number of drivers for each city type, including urban, suburban, and rural.  

     ![Fig1](https://user-images.githubusercontent.com/83401820/126107658-176d80d2-e110-424c-97ac-975611dc3c25.png) Note: Circle size correlates with driver count per city.   


#### Box-and-Whisker Plot  
- showcases the number of rides, fares and drivers for each city type.  
  
![Fig2](https://user-images.githubusercontent.com/83401820/126107659-045e2509-d655-43a9-ac77-848447252847.png)  
![Fig3](https://user-images.githubusercontent.com/83401820/126107660-d6556722-7c1c-4a82-851c-1d81efc8c055.png)  
![Fig4](https://user-images.githubusercontent.com/83401820/126107661-1ca06930-2b61-41ea-84af-2b87ceb1910f.png)    
  

#### Pie Chart  
- showcases the percent of total fares, rides, and drivers.  
  
![Fig5](https://user-images.githubusercontent.com/83401820/126107662-4be8e013-5267-435f-8b76-9ad211d7d01a.png)  
![Fig6](https://user-images.githubusercontent.com/83401820/126107664-306bfffc-dfb1-48f6-b941-7e99b6aa54e1.png)  
![Fig7](https://user-images.githubusercontent.com/83401820/126107665-424fe271-0d16-42ee-bf89-92f069006e70.png)    
  

#### Multiple Line Chart  
- showcases the total fares for each city type.  

![Fig8](https://user-images.githubusercontent.com/83401820/126107657-aa04a569-86bf-46a5-9aa9-d9414326c806.png)    


## Results  
Based on the bubble chart it is evident that more support is needed in the rural areas.    
In comparing the average number of rides between each city type,   
the average number of rides in the rural cities is about 4 and 3.5 times lower   
than urban and suburban cities, respectively.    

Based on the box-and-whisker plot, there is one outlier in the urban ride count data of 39.   
Also, the average number of rides in the rural cities is about 4 and 3.5 times lower per city   
than the urban and suburban cities, respectively. Once the outlier is removed, the data reveals  
that the fare in the rural areas is almost 2 times that of either the urban or suburban cities  
respectively. Referring back to the bubble chart, the reason for this could be attributed to a  
lack of demand.      

In examining and comparing the pie charts, however, it is quickly noted that the rural area is  
drastically underserved while the urban cities may, in fact, have too many drivers. Reallocation of  
some drivers from the urban cities into the rural cities could not only save money because there  
would be no need to hire new drivers while also increasing revenue by servicing the aforementioned  
areas in the rural cities.        

Finally, the multi-line chart gives a clear depiction that the rural cities have been consistently underserved.  

## Summary  
Based on these findings, three recommendations are to:  
- reallocate resources (i.e. drivers) from the urban to the rural cities,  
- as a result, fares should be re-examined to create a more uniform pricing structure, and finally  
- maintain the fare and driver ration in the suburban cities as it appears to be the baseline.  

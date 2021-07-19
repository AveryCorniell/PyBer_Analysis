# PyBer Analysis  

## Analysis Overview  
The purpose of this analysis is to provide PyBer Ride Sharing company with an exploratory analysis  
on Drivers, Dates, and Fares of Cities based on City Types (Urban, Suburban, and Rural), in the forms of several different visualizations, that will help Pyber to improve access to ride sharing services, as well as, determine affordability for potentially underserved neighborhoods.  

## Resources and Process 
Data Files:  
- city_data.csv  
    - 3 columns (city, driver_count, type)  
    - 120 records
- ride_data.csv  
    - 4 columns (city, date, fare, ride_id)  
    - 2375 records  
**(All imported data was clean and contained 4 months of rideshare data)**  

Open-Source Coding Software:    
    - Python       
    - Pandas 
    - Matplotlib (matplotlib library)  
    - Statistics  
    - Numpy  
    
Deliverables:   
**NOTE: Charts and graphs were plotted using both the MATLAB and Object-Oriented Approaches.**  
      **All charts were created uniformly with the following colors scheme:**   
        **coral for urban areas**  
        **skyblue for suburban areas**  
        **gold for rural areas**  
        
### Bubble Chart  
- showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.  
### Box-and-Whisker Plot  
- showcases the number of rides, fares and drivers for each city type.  
### Pie Chart  
- showcases the percent of total fares, rides, and drivers.  
### Multiple Line Chart  
- showcases the total fares for each city type.  

## Results  
Based on the bubble chart it is evident that more support is needed in the rural areas.  
In comparing the average number of rides between each city type,   
the average number of rides in the rural cities is about 4 and 3.5 times lower   
than urban and suburban cities, respectively.    

Based on the box-and-whisker plot, there is one outlier in the urban ride count data of 39.   
Also, the average number of rides in the rural cities is about 4 and 3.5 times lower per city   
than the urban and suburban cities, respectively. Once the outlier is removed, the data reveals   that the fare in the rural areas is almost 2 times that of either the urban or suburban cities   respectively. Referring back to the bubble chart, the reason for this could be attributed to a   lack of demand.      

In examining and comparing the pie charts, however, it is quickly noted that the rural area is   drastically underserved while the urban cities may, in fact, have too many drivers. Reallocation of  some drivers from the urban cities into the rural cities could not only save money because there    would be no need to hire new drivers while also increasing revenue by servicing the aforementioned   areas in the rural cities.      

Finally, the multi-line chart gives a clear depiction that the rural cities have been consistently   underserved.  

## Summary  
Based on these findings, three recommendations are to:  
- reallocate resources (i.e. drivers) from the urban to the rural cities,  
- as a result, fares should be re-examined to create a more uniform pricing structure, and finally  
- maintain the fare and driver ration in the suburban cities as it appears to be the baseline.  

# PyBer_Analysis.


The following analysis was created to a deep-down trough 4 months of rideshares. V.Isualize wanted to analyze if PyBer had the tools and resources applied to the cities selected.



After receiving the data with, we get to work with Omar merging the two csv files because the information necessary to complete the analysis, seems like data was collected on different days. Using Jupyter platform and Pandas, we could accomplished it.



![Screenshot (30)](https://user-images.githubusercontent.com/114957364/201491185-a99ac142-ca40-481a-922b-4158f5fcbd3a.png)






After data was merged data was cleaned and prepared for analysis checking for empty cells and corrupted data. Data was converted also in order to perform calculations.
Once data is clean, we proceed to create a new DataFrame with the headers of the data, doing this we could filtered the info in multiple ways like type of city, ride fares, by driver etc. 

Playing with the key elements we got the following answers:

•	Type of City: with more rides, ride fare avg, total fares 

•	By Driver: the avg fare per ride by city type, total amount of drivers 
    
    •	Rural type had the smaller number of rides but with the higher avg fare.
    •	Urban type had the highest number of rides but the lower avg fare 
    •	Suburban type is located right in the middle with all data collected  


![Screenshot (31)](https://user-images.githubusercontent.com/114957364/201491562-22c7fb0c-c9a3-4a2f-9bd6-4ce303c2e608.png)


### Filtering information.


after getting averages and percentages we could filter the results to get the exact information that we needed (2019-01-01 to 2019-04-29) to sum the fares and show results by week and then we create the line chart.
![download](https://user-images.githubusercontent.com/114957364/201491091-1ec25189-adc6-481f-a4dd-a44c9a6bf3b5.png)

# CityBike_NYC 
![alt text](https://raw.githubusercontent.com/mccallkm/CityBike_NYC/master/Images/citi-bike-station-bikes.jpg)

NY bike rides have been incrementally increasing since the first launch of Citi Bike in 2013. An analysis of the trends in number of users, subscriber type, where rides start and end were examined for January 2016 vs. January 2018. This data was limited to one month due to file size but can be replicated to analyze full years or specific quarters. 

The data sets were pulled directly from this source site: https://www.citibikenyc.com/system-data

Each excel file includes the following data elements:
Trip Duration (seconds)
Start Time and Date
Stop Time and Date
Start Station Name
End Station Name
Station ID
Station Lat/Long
Bike ID
User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
Gender (Zero=unknown; 1=male; 2=female)
Year of Birth

Data was prepped and cleaned using Python Pandas. Visualizations can be found in the Tableau workbooks saved in this repository. Note, Trip Duration was converted from seconds to hours, Gender values 0,1,2 we converted to their descriptors and Year of Birth was converted to a users age as of February 2019. 

For findings and analysis recap on the 2016 and 2018 data see the PowerPoint presentation in this repository.



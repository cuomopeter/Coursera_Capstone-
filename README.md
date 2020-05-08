

**Business Problem** 


  A venture capitalist has seen the recent housing boom in Atlanta, Georgia and is looking to start a small business in whichever areas have seen pronounced value increase. One assumption this venture capitalist is making, wherever he starts his business will see an increase in public spending as long as it is in a heavily gentrified area. This person is looking to do some initial research to identify those areas in Atlanta that have the highest percentage increase in home value. 
The capitalist is hoping to start a business while business zoned property is still relatively cheap, In order that in 10 years, a large profit can be made when selling. However, this person does not want to compete in a saturated market. Ideally, this initial data would lead into possible ideas and identify what types of business would add the most value to the local neighborhood. 

**Data Introduction**

For this assignment I will be using two data sources. One will be Foursquare venue data pulled from Folium geolocation points, after identifying those zip codes which have been most affected by the boom. The second data set will be pulled from Zillow housing research for average home prices. This data will be filtered to include all of Atlanta. It will need to be historical data, starting after the 2009 housing market crash. Ideally, we would have month by month value for each zip code. 

</br>
</br>
</br>

**Initial Zillow Data** 
All data for Atlanta and specifically Fulton county zipcodes

</br>

![](Capstone/Images/Picture1.png)

</br>
Pct_change function used to see month over month growth - still confusing

![](Capstone/Images/Picture2.png)
</br>
</br>
Filtered to show the top ten pct_change zipcodes and joined to $ amount zipcodes - here we can see a clear steep increase

![](Capstone/Images/Picture3.png)

</br>
</br>
Using Folium and a geolocater package I mapped these zipcodes - intersting to note they are all in southwest Atlanta

![](Capstone/Images/Picture4.png)


![](Capstone/Images/Picture5.png)


![](Capstone/Images/Picture6.png)


![](Capstone/Images/Picture7.png)


![](Capstone/Images/Picture8.png)


![](Capstone/Images/Picture9.png)

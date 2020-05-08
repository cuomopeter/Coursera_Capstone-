

# Business Problem 


  A venture capitalist has seen the recent housing boom in Atlanta, Georgia and is looking to start a small business in whichever areas have seen pronounced value increase. One assumption this venture capitalist is making, wherever he starts his business will see an increase in public spending as long as it is in a heavily gentrified area. This person is looking to do some initial research to identify those areas in Atlanta that have the highest percentage increase in home value. 
The capitalist is hoping to start a business while business zoned property is still relatively cheap, In order that in 10 years, a large profit can be made when selling. However, this person does not want to compete in a saturated market. Ideally, this initial data would lead into possible ideas and identify what types of business would add the most value to the local neighborhood. 

### Data Introduction

For this assignment I will be using two data sources. One will be Foursquare venue data pulled from Folium geolocation points, after identifying those zip codes which have been most affected by the boom. The second data set will be pulled from Zillow housing research for average home prices. This data will be filtered to include all of Atlanta. It will need to be historical data, starting after the 2009 housing market crash. Ideally, we would have month by month value for each zip code. 

<br />


# Methodology and Analysis 

I will first be looking at Zillow data to gather the zip codes with the highest increase, pertage, in home value. Then I will separate out those zip codes, geolocate to find their coordinates, and explore venues in the area. After exploring venues, I will analyze for possible business ideas and saturated markets. If further analysis is needed, I will perform that analysis using these two data sources.

<br />

All data for Atlanta and specifically Fulton county zipcodes

<br />

![](Capstone/Images/Picture10.png)

<br />

![](Capstone/Images/Picture1.png)

</br>

Pct_change function used to see month over month growth - still confusing

![](Capstone/Images/Picture2.png)

<br />
Filtered to show the top ten pct_change zipcodes and joined to $ amount zipcodes - here we can see a clear steep increase
<br />

![](Capstone/Images/Picture11.png)
![](Capstone/Images/Picture3.png)

<br />
Using <b>Folium and a geolocater</b> package I mapped these zipcodes - intersting to note they are all in southwest Atlanta

<br />

![](Capstone/Images/Picture12.png)
![](Capstone/Images/Picture4.png)

<br />
Next using <b>FourSquare API</b> I sorted the top venue types in atlanta for exploration
<br />

![](Capstone/Images/Picture13.png)
![](Capstone/Images/Picture5.png)

<br />
I wanted to dig deeper to see where the trail venues were located, so using the geolocation from the FourSquare API:
<br />

![](Capstone/Images/Picture14.png)
![](Capstone/Images/Picture6.png)

<br />
It appears most of the venues are <b>one</b> trail system - westside Atlanta Beltline
<br />
![](Capstone/Images/Picture7.png)

<br />

So, it looks as if this trail system is  under developed in terms of venue diversity but I wanted to do a but more exploration on the matter. I retrieved all of the data from more developed trail system venues. Specifically, I looked at Dallas, Chicago, and New York trail systems. Within a 1 miles radius of these trail systems, here are the most prevalent small businesses. 
</br>

![](Capstone/Images/Picture15.png)
![](Capstone/Images/Picture16.png)
![](Capstone/Images/Picture17.png)
![](Capstone/Images/Picture8.png)

<br />
Extracting 'park' or 'trail' from the mix and returning the top four small businesses in more developed areas:

![](Capstone/Images/Picture9.png)


### Results

The results of our analysis show that the trail system found in west Atlanta is a key interest point. It is the most prominent feature in foursquare API. What is more, we can see that other large cities have similar trail systems. Because of the recency of the Atlanta housing market boom, the venues of other large metro area trail systems are very different. The most popular types of venues within 2 miles of the trail systems in other major cities are: Ice Cream Shops, Breweries, Coffee Shops, and Bakeries. 

<br />
<br />

### Further Discussion 

It was interesting to note that all of fastest gorwing value homes are all in southwest Atlanta. Being from Atlanta, one would not think this to be the case. However, it is clear that the Atlanta beltline, which started on the eastside of town, is now making its way to the westside. It has made a monumental impact on the eastside economy and further analysis on the store fronts in eastside zip codes would be interseting to show what is available. In zip code 30310, this had the most prominant value increase. This is also the zipcode where the westside beltline is found.

# Conclusion 

Looking at the venue area data from the top most gentrifying zip codes in Atlanta, it is clear that there is an opportunity in the vast Westside Atlanta Beltline area for small business. Right now is an opportunity for a savvy investor to purchase property close to or on the Westside Atlanta Beltline, open a brewery, coffee shop, ice cream shop, or bakery because people love to eat before, during, or after walks, as the data shows!


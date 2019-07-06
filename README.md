# Where should you book your next _Airbnb_?
## An Airbnb Data Visualization Project
| Data Mingling | Data Cleansing | Data Visualization | Animation |  
| Jupyter Notebook | Python | Google API | Pandas | Matplotlib | Seaborn |  

Members: Murali Calambur, Anuj Desai, Santosh Singh, Estella Yu  (by last name)

[![Watch the video](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/working/Output/Gmaps_Visualization/Animation/airbnb_listing.gif)](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/working/Output/Gmaps_Visualization/Animation/airbnb_listing.gif)

[**Airbnb Inc.**](https://www.airbnb.com/) is an American hospitality service brokerage company based in `San Francisco, California`, United States. Members can use the service to arrange or offer lodging, primarily homestays, or tourism experiences (from [wiki](https://en.wikipedia.org/wiki/Airbnb)). Founded in `2008` by Brian Chesky, Joe Gebbia, and Nate Blecharczyk, Airbnb has received vase attention worldwide and has hosted `400 million` (that's 8 zeros..) guests since its launch.

In a metropolis like New York City, millions of tourists are expected every month, [according to the latest tourism statistics](https://www.nytimes.com/2019/01/16/nyregion/nyc-tourism-record.html). Despite the hotels all over the city, sometimes it's just `DIFFICULT` to find a decent room to stay at (and you surely know how hard it is...) And sometimes, it's just `TOO EXPENSIVE`. 

**So Airbnb becomes your next choice in hand!** In fact, NYC is one of the most popular Airbnb hosting sites worldwide, along with Tokyo and Paris. So, if you are about to travel to NYC, what are some tricks to look for in order to save some more bucks?
## Some Take Home Messages
### 1. Some Airbnb Historic Facts in NYC
####  1) You have A LOT of options
  * The first Airbnb listing in NYC was available in Aug 2008 (VERY soon after the site had been launched). 
  * Fast forward to today, there are over **48k listings** available in NYC.
  * If you are a `tourist` -- this means you will be flooded with tons of options  
    If you are a `New Yorker` who wants to get on the hosting boat -- You might want to consider where to place your listing on this already crowded map. But considering that the **_new listings per year has already seemed to peak in 2005_**, you might have a chance to stand out afterall. 


![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/working/Output/Historic_Accumulate_Listing_Count_ALLTIME.png "Airbnb Listings in NYC")

#### 2) $$$ PRICE, PRICE, PRICE $$$, and more
  * Despite the almost _continuously increasing trend in total active listing number_, there's a **sharp drop in price** during Q3 2015. The average price has been steadily decreasing since then
  * Of all three roomtypes available (`Entire Apt`, `Private Room`, `Share Room`), the majority of the listings are either `Entire Apt` or `Private Room`, so you probably don't need to worry about trading off your privacy for not staying in a hotel  
  
![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/working/Output/Histroric_Listing_Count_and_Average_Price.png "Airbnb Listings Price in NYC")

## Data Source: 
[Inside Airbnb](http://insideairbnb.com/): `Listing`, `Reviews` and `Calendar` .csv datasets  
[Tom Slee Airbnb](http://tomslee.net/category/airbnb-data): Airbnb datasets in New York, with `historical listing price` included  
[Google API](https://console.developers.google.com): Retrieve goolge map location with (lat, lng) coords

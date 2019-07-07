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

### 2. Party Size & Room Type (Manhattan)
It's for sure that `Entire Apt` can provide you the best privacy, and you might think that maybe sacraficing a little privacy and going for `Private Room` can save you some bucks. Well, according to the analysis, **it might NOT be so SIMPLE**

#### 1) Book with a **`Bigger Party`** & **`Save More`**
  * In general, there are `more options` with `smaller party size`
  * According to the `Median`, booking with a `larger pary size` can overall `save more $$$` 
  * You can, of course, go for a **fancy** Airbnb option easily in Manhattan, since there are LOTS of expensive outliers across all party sizes 
  
![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/estella/Output/AveragePriceDistBoxPlot.png "Box plot Accommodation & Room Type in NYC")

#### 2) There is an **`Optimum Pary Size`** for each Room Type
  * In general, it's true that the price/person (with cleaning fee) rank as: `Entire Apt` > `Private Room` > `Share Room`. **But**, there is an **`Optimum Pary Size`** that can help you to save the most!
     * If you are a `privacy person` -- Try `Entire Apt`. Booking with a group size `5-9` can offer you the cheapest price per person in Manhattan
     * If you are more towrads an `interaction person` -- Try gather a group of `3-4` friends with `Private Rooms` booking!  

![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/estella/Output/MeanPriceByRoomTypes.png "Accommodation & Room Type in NYC")

### 3. Where Should I Book?
_"How awesome is that if I can stay in Time Square! But if I can't afford it just yet, where can I find the next best?"_  
You can probably find the answer in the following box chart, which sorts the regions based on `median price/person`. 
* There is a general trend that the Airbnb `price/person` **`increaeses`** `from uptown to downtown`:  
  * The 3 `lowest cost` regions: `Inwood and Washington Heights` (lowest), `Central Harlem`, `East Harlem`
  * The 3 `most expensive` regions: `Greenwich Village and Soho` (most expensive), `Chelsea and Clinton`, `Lower Manhattan`
  
* If you want to hack the price around, you might want to try some mid-priced area. (Why not having a nice location & cheaper price !)

![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/estella/Output/priceperregion.png "Regional in NYC")

![alt text](https://github.com/EstellaYu/Data_Visualization_Airbnb_Hotel/blob/estella/Output/RegionalPricing_Map.png "RegionalPriceMap")

## The Ultimate Summary

##### * Airbnb can be a great option if you are traveling in NYC (offering cheaper lodgging options compared to hotels, and a different city experience)
##### * You have a lot of options -- There are more than `49k` Airbnb in NYC, and `~15k` in Manhattan alone
##### * You can pick your favorate region based on your budget $$$ and the price map above
##### * Try to go with a larger party -- a group of `5-9` is the cheapest with `Entire Room`, and `3-4` is the optimum size with `Private Room`. 
#### `ENJOY YOUR TRIP IN NYC!`

## Data Source: 
[Inside Airbnb](http://insideairbnb.com/): `Listing`, `Reviews` and `Calendar` .csv datasets  
[Tom Slee Airbnb](http://tomslee.net/category/airbnb-data): Airbnb datasets in New York, with `historical listing price` included  
[Google API](https://console.developers.google.com): Retrieve goolge map location with (lat, lng) coords

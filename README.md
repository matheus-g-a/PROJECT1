# PROJECT1
## How Many Breweries are in the United States Total and Per State? 

To determine this question, the first step was to find data on United States Breweries. The exploration of data lead to many other questions surrounding validity of data and parameters of the search. Ultimately, the data sets that were used came from government entities. In order to avoid data being skewed by COVID shutdowns, the year 2019 was examined. Population data per state was pulled from the Census Bureau's Population API. Counts of Breweries per state was obtained via The Alcohol and Tobacco Tax and Trade Bureau. Their counts are based on operating permits. This data only includes facilities where beer is brewed, so excludes venues who's sole purpose is consumption - like taprooms. 

### Results

Overall, there were 11,584 breweries with operating permits accross the United States. The average number of breweries per state is 231, however this number is skewed. The state with the most number of breweries is California, with 1370. The state with the least amount of breweries is Mississippi with only 22. The image, "Breweries per State" is a visual representation of the number of breweries per state. The image, "Breweries per State versus Population" is a visual representation of the number of breweries per state compared to population. In the image, there is one marker per state located at the state's population (in millions). The color of the marker is indicative of how many breweries are in the state. For example, since California has the most breweries, its marker is the darkest color, while Mississippi's is the lightest color since they have the least number of breweries. 

***Breweries per State***

![This is a bar graph representing the number of breweries per state.](https://github.com/matheus-g-a/PROJECT1/blob/b1c76f4f8873b6b84ebe898292d1b75abf1e0db4/Brew_Count.png)

***Breweries per State versus Population***

![This image contains markers located at population counts per state with colors of the markers representing the count of breweries per state.](https://github.com/matheus-g-a/PROJECT1/blob/b1c76f4f8873b6b84ebe898292d1b75abf1e0db4/breweries_pop_scatter_2019.png)


The data analysis that went into obtaining these results can be found in the Jupyter notebook file entitled "brewery_state_population.ipynb". [brewery_state_population.ipynb](https://github.com/matheus-g-a/PROJECT1/blob/b1c76f4f8873b6b84ebe898292d1b75abf1e0db4/brewery_state_population.ipynb)

## Top 10 Beers Consumed by Americans

In order to figure out which beers Americans love the most, we first had to find data on the kinds of beer sold in America using sales and ratings information. Although beer revenue in the U.S. amounts to approximately $120 billion dollars annually, it turns out that raw sales data is very difficult to attain. We relied on CSV files of different kinds of craft beer sold in the U.S., as well as data that included comprehensive consumer review information about the appearance, aroma, palate, and taste profiles of many different styles of beer. 

(https://github.com/matheus-g-a/PROJECT1/blob/190c4ece52587345a388ed81315344448c7a41b5/Craft%20Beers%20Dataset/Top10.png)

## Results

According to the data, the most popular beer for Americans is American IPA. This beer is typically described as being floral, fruity and aromatic, and has an average alcohol by volume of 6.9%. American Pale Ale comes in second with a softer and less bitter mouth feel, and an overall lower percentage of alcohol by volume at 5.6%. The third most popular beer should also be noted for having only 4.77% alcohol by volume on average, suggesting that American's prefer their beer to come with fuzzy feelings of happiness. The data losely suggests that aromatic and fruity beers tended to have higher rating, whereas astringency is often associated with a lower rating. However, it should be stated that no strong correlations between flavor and ratings could be deciphered, suggesting that a cold beer is a good beer.


## Age Groups vs Brewery Count


  For this analysis I wanted to explore the relationship between the amount of breweries compared to the age groups outlined in the US Census. 
Some of the limitations with the data were that the age groups were pre determined, therefore some people that were younger are left out of the data set. However,the argument for how many twenty one through twenty three year olds prefer breweries to nightclubs, bars etc can be made on a separate analysis.  Lastly, sorting data was a nightmare. The US Census has so much data with different variables that will be called index, as well as different formats such as JSON, csv or shp, in my case. Therefore, learning how to manipulate and sort data was where the majority of my time went. Graphing the data was also a challenge, since choropleth map in python was new to me. In addition, learning how to overlay or add text that hovers allowed me to add all the information needed to the graphs. In total I had three graphs that accounted for the pre-determined groups (24-34, 35-54, 55-64) 

![Adults 26-34](https://user-images.githubusercontent.com/111663647/228099450-61bfafe6-c747-4404-95d2-c970b7e1ef59.jpeg)
![Adults 34-54](https://user-images.githubusercontent.com/111663647/228099493-44a7c960-0948-4b09-8631-bb8d1a7feb13.png)
![Adults 55-64](https://user-images.githubusercontent.com/111663647/228099502-84f285c6-169a-42b9-b490-aad5739cc0a7.png)

##Results

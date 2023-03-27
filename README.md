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

In order to figure out which beers Americans love the most, we first had to find data on beer sold in America and sales or rating information. It turns out that sales data is very difficult to attain with a free API, so we relied on csv files that were compiled of different kinds of canned beer sold in the U.S. We also examined data that included comprehensive consumer review information about the appearance, aroma, palate, and taste profiles of many different styles of beer.

### Results

According to the data, the most popular beer for Americans is American IPA. This beer is typically described as being floral, fruity and aromatic, and has an average alcohol by volume of 6.9%. The data showed us that aromatic beers tended to have higher rating. American Pale Ale comes in second with a softer and less bitter mouth feel, and overall lower percentage of alcohol by volume of 5.6%. 

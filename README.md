# Final-Project-Tableau

## Project/Goals
To investigate the potential factors impacting Airbnb prices within the state of New York by analyzing Airbnb host data ranging from 2008-2015

## Process
1. Gather information on Airbnb host data
2. Import dataset in Tableau to investigate information
3. Analyze categories and data types through inspection and data visualization
4. Identify trends, patterns and outliers
5. Generate hypothesis, potential question and points of interest
6. Create visualizations including maps, tables and graphs to present findings to potential audiences
7. Construct dashboards consisting sheets created in previous step
8. Present findings

## Results
### MAIN QUESTION: What are the factors impacting Airbnb prices in New York City?
### Sub-Questions:
1. How have the # of available listings changed from 2008 to 2015
2. Do hosts typically own one or multiple listings?
3. For hosts who own multiple properties, do they typically invest in a single borough or different ones?
4. Which borough has the highest average price per night?
5. From the listings, what does the distribution of room types across different boroughs look like?
6. Which type of property is most popular amongst consumers?
7. What is the most popular price range amongst consumers in NYC?
   
### RESULTS
When investigating price fluctuations, it is important to investigate the problem from both the perspectives of supply and demand. The first three questions are designed to investigate the price determinates from the supply perspective whereas the last three seek to answer the problem from the demand perspective. 

To investigate the determinates for price, attention needs to be brought towards the hosts themselves. Within an open market host are essentially price setters whose ability to raise prices are depend on their amount of market power. The surge in US housing market prices resulted in an abundance of new host from the years of 2013 onward, all of which had been granted the freedom to charge higher prices for occupation of their properties; many of which operating through multiple properties. The increase in housing prices, paired with the operation of multiple properties had granted Airbnb host an abundance of market power, enabling said host to charge higher prices. Amongst the hosts who own multiple properties, many typically invest in a single borough as opposed to diversifying their housing portfolios.

Despite approximately 69% of hosts across NYC only operating a single property, the findings may be misleading. For instance, more than half of the hosts operating within the boroughs of Staten Island and Bronx own multiple properties. Within Staten Island, there are a minimal number of listing available, thus, the hosts with multiple properties have larger market shares, enabling them to price gouge consumers – i.e., higher prices.

In regards to demand, location play a crucial role in determining prices as higher in demand areas such as Manhattan typically cost more than other boroughs such as the Bronx. As expected, Manhattan has the highest average price/night as it contains a majority of the state’s attractions, such as Time Square; when people voice their desire to visit NYC, they typically mean Manhattan.

Utilizing the number of reviews any given listing possesses as an indicator/proxy for popularity, apartments are by far the most popular in regards of listings and number of reviews. This finding makes sense both geographically and demographically as in densely populated areas, such as Manhattan, there simply is not enough space to construct other larger forms of property. 

When analyzing the most popular price ranges, it should come as no surprise the cheaper options tend to be more popular. When setting prices, hosts may be tempted to establish absurdly high rates ranging upwards of $2000 per night – however, how many consumers would be willing to pay said price? When visiting a foreign destination, travellers typically spend minimal time within a luxury hotel; rather they typically leave their belonging in said rental property as they conduct their business, forgoing the need for the luxuries associated with expensive properties. 


## Challenges 
- Tableau's lack of geographical information on NYC's boroughs requiring the addition of further spatial files
- Organising visualizations in a manner which depicts a story

## Future Goals
- Investigate relationship with time series data instead of cross sectional
- Look at other potential variables such as seasonality 
- Create regression models to test strength explanatory variables

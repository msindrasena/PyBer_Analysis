# PyBer_Analysis
## Intro Paragraph

### Background and Results
The purpose of this assignment was to analyze key metrics for Pyber by city type, including: total rides, drivers, fares, average fair per ride, and average fare per driver. I analyzed the data by merging the two CSV files given and using the groupby() function to count and sum up requested metrics. I used simple mathematic equations for Average fare per ride and Average fare per driver and then formatted into a single dataframe. 
It is very clear in the summary DataFrame that the city type ‘Urban’ has quite a lot more total rides, drivers and fares than those of Suburban or Rural communities. In the Multiple-Line graph, it similarly shows that the gold line “urban” is at the top of the chart with total fares way higher than the other two city types. 

[Image of DataSummary](analysis/Fig8.png)
[Image of Multiple Line Chart](analysis/Fig9.png)

In Summary, Ubran cities are much more bustling and happening! There are more people needing more rides, which also increases the number of drivers and total fares. The average fare per ride and fare per driver for Urban are less than Suburban and Rural.

## Second Parapgraph
### Challenges Encountered and Overcome
Some of the challenges I encountered were the number of DataFrames we were asked to create. Each time you make a new DataFrame, there is room for human error. Because of this, it is very important you create a plan before starting your code so you know when its appropriate to create a a new DataFrame and follow along as you make your way down the assignment. As you can see in this image, I have created a plan prior to starting to help guide me: [Imaage of Plan](analysis/Plan.PNG)

Another challenge that I encountered was formatting summary Dataframes that have NAN values into something that can be summed up. It was essential to make NAN values a 0, so it would be easy to sum up the total fares based on city type. After many attempts of trial and error and fixing the code, I was finally able to get a total sum rather than NAN's or 0's. [Image of Nan](analysis/Nan.png)

Another formatting challenge was that my date was formatted differently from the Module, (2019-01-01, rather than 01/01/2019) so its important to see how your data output shows so when creating a date range, you are using the appropriate formatting!

## Third Paragraph
### Reccomendations and Next Steps

It would be interesting to find out how long a typical ride is or the distance of these rides. For the CEO of a ride-sharing app, I would want to see the typical types of rides our clients take: whether than is a 5-8 quick ride to work in a bustling city, or a 15-20 commute to a friends house in the suburbs. After getting this data, I would add this to the summary DataFrame and total the time it takes for each city type and find an average trip time per driver and ride by diving that number by the total number of drivers and rides! 
This could also provide more information on the rides for Urban cities. In general, the average fair per driver for Urban drivers is much less than those of Suburban and Urban areas, and they are doing a lot more rides. When thinking about driver equity, it is important that drivers are making a decent living while not being overworked! Also, how many rides are crossing city types? This information may tweak our data. 

I think analyzing Urban statistics more deeply is cruical. With the rise of ride-sharing apps, cities have become historically more congested. Looking more closely at the time of day rides are requested can help the CEO determine when clients are in need of rides and how we they can better use data to take alternative routes and help the city. We could use any of the DataFrames that included date with the time.  Also, looking at the distance as previously mentioned can also help determine what types of vehicles should be on the road and can help limit unecessary gas emissions. We could use create a Dataframe for each city type with the kind of car they are using and determine what may be the most cost/fuel efficient for Pyber which would also benefit the cities they run in. 

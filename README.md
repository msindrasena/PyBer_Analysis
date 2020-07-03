# PyBer_Analysis
## Intro Paragraph

### Purpose
The purpose of this assignment was to analyze key metrics for Pyber by city type, including: total rides, drivers, fares, average fair per ride, and average fare per driver. I analyzed the data by merging the two CSV files given and using the groupby() function to count and sum up requested metrics. I used simple mathematic equations for Average fare per ride and Average fare per driver and then formatted into a single dataframe. 
It is very clear in the summary DataFrame that the city type ‘Urban’ has quite a lot more total rides, drivers and fares than those of Suburban or Rural communities. In the Multiple-Line graph, it similarly shows that the gold line “urban” is at the top of the chart with total fares way higher than the other two city types. 

[Image of DataSummary](analysis/Fig8.png)
[Image of Multiple Line Chart](analysis/Fig9.png)

In Summary, Ubran cities are much more bustling and happening! There are more people needing more rides, which also increases the number of drivers and total fares. The average fare per ride and fare per driver for Urban are less than Suburban and Rural.

## Second Parapgraph
Some of the challenges I encountered were the number of DataFrames we were asked to create. Each time you make a new DataFrame, there is room for error. So its very important you create a plan before starting your code so you know when its appropriate to createa a new DataFrame and follow along as you make your way down the assignment. As you can see in this image, I have created a plan prior to starting to help guide me: [Image of Plan](analysis/Plan.png).

Another challenge that I encountered was formatting summary Dataframes that have NAN values into something that can be summed up. It was important to give NAN values a 0, so it would be easy to sum up the total fares based on city type. After many attempts of trial and error and fixing the code, I was finally able to get a total sum rather than NAN's or 0's. 

Originally, my date was formatted differently from the Module, (2019-01-01, rather than 01/01/2019) so its important to see how your data output shows so when creating a date range, you are using the appropriate formatting. 

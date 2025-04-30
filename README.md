# Group-Project-2

## Team Name: 
11157 Group 1

## Team Members 
1. Sierra McArter
2. Nick Cappel
3. Luca Davidson
4. Jada Tucker

## Dataset Description 
The dataset was obtained from the NOAA (National Oceanic and Atmospheric Administration) Storm Events Database, which collects and publishes detailed information on severe weather events across the United States. This includes events such as tornadoes, floods, hailstorms, and hurricanes. The data is compiled by the National Weather Service (NWS) and made publicly available for research and public safety purposes. The dataset has 1,814 rows and 51 columns. Some of the most insightful columns include magnitude, which measures the severity of the storm (data type: numeric/float), latitude and longitude which together coordinate where the storm occurred (data type: numeric/float), event type which is the type of weather event (data type: text/string), month the event took place (data type: integer), and State where the event occurred (data type: text/string).


## Questions 
Our first question focused on finding the average magnitude of the most frequent event type in each state during sever weather season (May-September). This is an important question to consider because May to September is peak severe weather season. By focusing on the most frequent event type per state, this question highlights what each region is most commonly exposed to. Storm magnitude often correlates with potential damage.Our second question analyses tornado behavior in the midwest, comparing width and path length. This is a valuble question because the midwest region is a tornado hotspot, often experiencing some of the most destructive tornados in the country. Investigating the correlation between tornado width and path length can help identify patterns in tornado behavior that may help inform things like: preparedness strategies,emergency response plans, and infastructure design. 

## Manipulations Applied to the Dataset
In order to maximize the relevancy of our question we had to manipulate and refine the data. For question 1 we refined the data to only include state,event type,month,magnitude,year, and date. State will idenfity the geogrphic location of events.Event type allows for filtering by the most frequent event type. Month restriction enables filtering from may through september. Year and date are used for time-trend breakdowns.For question 2 we filtered by state,average width, event type, and average length. State filters the data to midwest states only. Average width and length measures the average width and length by state to help identify how destructive the tornado is. Event type ensures we are refining to only tornado events. 

## Analysis and Results 

## Tableau Workbook 

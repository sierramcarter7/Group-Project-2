# Group-Project-2

## Team Name: 
11157 Group 1

## Team Members 
1. Sierra McArter snm11157@uga.edu
2. Nick Cappel nmc95998@uga.edu
3. Luca Davidson lmd70396@uga.edu
4. Jada Tucker jet97556@uga.edu

## Dataset Description 
The dataset was obtained from the NOAA (National Oceanic and Atmospheric Administration) Storm Events Database, which collects and publishes detailed information on severe weather events across the United States. This includes events such as tornadoes, floods, hailstorms, and hurricanes. The data is compiled by the National Weather Service (NWS) and made publicly available for research and public safety purposes. The dataset has 1,814 rows and 51 columns. Some of the most insightful columns include magnitude, which measures the severity of the storm (data type: numeric/float), latitude and longitude which together coordinate where the storm occurred (data type: numeric/float), event type which is the type of weather event (data type: text/string), month the event took place (data type: integer), and State where the event occurred (data type: text/string).


## Questions 
Our first question focused on finding the average magnitude of the most frequent event type in each state during the month of July. This is an important question to consider because May to September is peak severe weather season. By focusing on the most frequent event type per state, this question highlights what each region is most commonly exposed to. Storm magnitude often correlates with potential damage.Our second question analyses tornado behavior in the midwest, comparing width and path length. This is a valuble question because the midwest region is a tornado hotspot, often experiencing some of the most destructive tornados in the country. Investigating the correlation between tornado width and path length can help identify patterns in tornado behavior that may help inform things like: preparedness strategies,emergency response plans, and infastructure design. 

## Manipulations Applied to the Dataset
To maximize the relevancy of our question, we had to manipulate and refine the data. For question 1, we refined the data only to include state, event type, month, magnitude, year, and date. The state will identify the geographic location of events. Event type allows for filtering by the most frequent event type. The month restriction will enable us to only include events in the month of May. Year and date are used for time-trend breakdowns. To create a map visual, we used latitude and longitude for the rows and columns and selected a map from the marks card drop-down options. From there, we have a basic map visual. To filter for a specific month, we dragged "Month Name" to the filters box and only checked the month of May. Magnitude is automatically calculated as a sum. To change it to an average calculation, we right-click the magnitude pill after dragging it to the color box in the marks card and navigate down to the "measures" drop-down and select "average".By dragging magnitude to the color box, we are also making the different states color-coded by magnitude intensity, adding visual appeal and clarity. For question 2, we filtered by state, average width, event type, and average length. State filters the data to the Midwest states only. Average width and length measures the average width and length by state to help identify how destructive the tornado is. Event type ensures we are refining to only tornado events. To filter the states to only include midwestern states, we dragged the states pill to the filters box and only selected Minnesota, Missouri, Nebraska, North Dakota, Ohio, South Dakota, and Wisconsin. We did the same process to filter the event type for tornadoes. Similarly to the process used for question 1, we switched the length and width of tornadoes from sum to average. To create more visual appeal, we dragged the state pill to the text box within the marks card. This added the name of the state to the top of each bar within the graph making them easier to read and providing clarity. Additionally, we filter by color by dragging the average tornado length and average tornado width to the color box within the marks card. 

## Analysis and Results 
<img width="1055" alt="Screenshot 2025-04-30 at 3 27 50 PM" src="https://github.com/user-attachments/assets/c081c0ed-6a4a-410e-a975-e5f7d854aed1" />
Looking at the graph, you can see that the event types are divided by color. Pink for hail, blue for thunderstorms and wind, and yellow for tornadoes. The numbers in each state represent the average magnitude. Evidently, hail is the most prominent event in the U.S, and it can be found mostly in the Midwest. North Dakota has the thunderstorm with the highest magnitude at 70.00. Florida has the highest frequency of tornadoes. 

<img width="1064" alt="Screenshot 2025-04-30 at 3 03 49 PM" src="https://github.com/user-attachments/assets/cb6860cd-7c79-4222-ad94-62e9a20b4ab4" />
Looking at the graph, you can see that Wisconsin has the highest average tornado width and length, followed closely by Minnesota. Nebraska has a relatively high average tornado length, but the width is moderate, implying long-traveling but narrow tornadoes. Additionally, there is a visual correlation where states with higher width tend to also have higher length, like Minnesota and Wisconsin. States like Wisconsin and Minnesota might require more robust disaster preparedness due to larger tornado dimensions. Tornadoes in Missouri and Ohio appear wide but short, suggesting they may be powerful but localized. 


## Tableau Workbook 

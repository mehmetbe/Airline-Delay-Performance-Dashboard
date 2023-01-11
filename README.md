# Airline Performance and Delay Dashboard
This code creates a dashboard that returns various graphs and charts visualizing US airline performance and delay data between 2005-2020. The dashboard is created in Python Dash library.

In the dashboard, there are two dropdown menus where you can choose the report type and the year. You would first choose one of the two report type options, namely Yearly Airline Performance Report and Yearly Airline Delay Report; and then select a year to get the charts for the given year.

Each airline is represented by their IATA code in the graphs(e.g. American Airlines=AA).

## Yearly Airline Performance Report

Selecting this option and a year will populate 5 graphs to the dashboard. In the screenshots below, the year 2005 was selected for demonstration purposes.

### Flight count by airline to destination state

This is a treemap chart that gives number of flights flying to each state from each reporting airline.

![newplot](https://user-images.githubusercontent.com/112036107/211930828-a2b2af79-aed8-4654-9f7d-fb9125616692.png)

### % of diverted flights by reporting airline

This is a bar chart that gives the percentage of diverted airport landings per reporting airline.

![newplot (1)](https://user-images.githubusercontent.com/112036107/211933223-d0ed606c-f093-43b0-a75f-4e8ac6836e68.png)

### Number of flights from origin state

This is a choropleth map that shows the number of flights flying from each state.

![newplot (2)](https://user-images.githubusercontent.com/112036107/211933878-5a4454de-4775-4c37-8578-9d48009666a3.png)

### Monthly flight cancellation

This is a bar chart showing number of flights under different cancellation categories.

![newplot (3)](https://user-images.githubusercontent.com/112036107/211934591-b90322ca-3c36-4571-bfc7-5179f7bb2cd8.png)

### Average monthly flight time (minutes) by airline

This is a line chart showing Average flight time by reporting airline.

![newplot (4)](https://user-images.githubusercontent.com/112036107/211934785-03c42c21-ed04-4391-ae32-20c85444ac30.png)





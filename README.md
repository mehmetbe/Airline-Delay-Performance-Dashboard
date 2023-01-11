# Airline Performance and Delay Dashboard
This code creates a dashboard that returns various graphs and charts visualizing US airline performance and delay data between 2005-2020. The dashboard is created in Python Dash library.

In the dashboard, there are two dropdown menus where you can choose the report type and the year. You would first choose one of the two report type options, namely Yearly Airline Performance Report and Yearly Airline Delay Report; and then select a year to get the charts for the given year.

Each airline is represented by their IATA code in the graphs (e.g. American Airlines=AA).

## Yearly Airline Performance Report

Selecting this option and a year will populate 5 graphs to the dashboard. In the screenshots below, the year 2005 was selected for demonstration purposes.

### Graph 1- Flight count by airline to destination state

This is a treemap chart that gives number of flights flying to each state from each reporting airline.

![newplot](https://user-images.githubusercontent.com/112036107/211930828-a2b2af79-aed8-4654-9f7d-fb9125616692.png)

### Graph 2- Percentage of diverted flights by reporting airline

This is a bar chart that gives the percentage of diverted airport landings per reporting airline.

![newplot (5)](https://user-images.githubusercontent.com/112036107/211937484-7a394cb5-205e-4a25-9c3f-e20e444ec801.png)

### Graph 3- Number of flights from origin state

This is a choropleth map that shows the number of flights flying from each state.

![newplot (2)](https://user-images.githubusercontent.com/112036107/211933878-5a4454de-4775-4c37-8578-9d48009666a3.png)

### Graph 4- Monthly flight cancellation

This is a bar chart showing number of flights under different cancellation categories.

![newplot (3)](https://user-images.githubusercontent.com/112036107/211934591-b90322ca-3c36-4571-bfc7-5179f7bb2cd8.png)

### Graph 5-Average monthly flight time (minutes) by airline

This is a line chart showing Average flight time by reporting airline.

![newplot (4)](https://user-images.githubusercontent.com/112036107/211934785-03c42c21-ed04-4391-ae32-20c85444ac30.png)


## Yearly Airline Delay Report

Selecting this option and a year will populate 5 line charts to the dashboard. In the screenshots below, the year 2012 was selected for demonstration purposes. 

### Line Chart 1- Monthly average carrier delay time (minutes) by reporting airline 

![newplot (6)](https://user-images.githubusercontent.com/112036107/211939669-3b4b683f-e138-4b9d-8d95-5a29811ca1c8.png)


### Line Chart 2- Monthly average weather delay time (minutes) by reporting airline

![newplot (7)](https://user-images.githubusercontent.com/112036107/211939765-2a3d388d-5cf4-4a92-9fa5-b22eef1e59f5.png)

### Line Chart 3- Monthly average NAS (National Airline Security) delay time (minutes) by reporting airline

![newplot (8)](https://user-images.githubusercontent.com/112036107/211939854-75835a20-0d89-4f4b-800f-ff035cd12553.png)

### Line Chart 4- Monthly average security delay time (minutes) by reporting airline

![newplot (9)](https://user-images.githubusercontent.com/112036107/211939922-fd022934-2092-41c1-b903-c204f80f6dc0.png)

### Line Chart 5- Monthly average late aircraft delay time (minutes) by reporting airline

![newplot (10)](https://user-images.githubusercontent.com/112036107/211939999-ee95189a-4950-402e-9944-6d9681dce4d1.png)







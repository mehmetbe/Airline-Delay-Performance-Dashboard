# Airline Performance and Delay Dashboard
This code creates a dashboard that returns various graphs and charts visualizing US airline performance and delay data. Dashboard is created in in Python Dash library.

In the dashboard, there are two dropdown menus where you can choose the report type and the year. You first choose one of the two report type options, namely Yearly Airline Performance Report and Yearly Airline Delay Report; and then select a year to get the charts for the given year.

Each airline is represented by their IATA code in the graphs(e.g. American Airlines=AA), looking up each IATA code online will give you the full name of the airline.

## Yearly Airline Performance Report

Selecting this option and a year will populate 5 graphs to the dashboard:

### Flight Count by airline to destination state

This is a treemap chart that yields number of flights flying to each state from each reporting airline.

![newplot](https://user-images.githubusercontent.com/112036107/211930828-a2b2af79-aed8-4654-9f7d-fb9125616692.png)



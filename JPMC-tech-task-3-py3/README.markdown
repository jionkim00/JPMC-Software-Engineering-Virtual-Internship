# Task 3: Display data visually for traders
Use Perspective to create the chart for the trader's dashboard.

## Background Info:
Being able to access and  adjust data feeds is critical to any trading analysis and stock price monitoring. From the previous tasks, we now have the adjusted data set up on your systems and being piped into Perspective.

For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstation.

Given there is a lot of information and data being produced at once, visualizing data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

You will use perspective to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor this trading strategy.

## Tasks Completed:
* Changed Graph.tsx to have the schema to include the properties ratio, upper_bound, lower_bound, and trigger_alert to implement the bounds and alert features. Other configurations were made in order to utilize the updated properties.
* Changed DataManipulator.ts and its Row interface to process the new schema with its new properties.
* Created custom bounds in which an alert would be set.
* Outcome:The numbers from the python script now render properly in the live perspective graph. This means the ratio between the two stock prices is tracked and displayed. The upper and lower bounds are displayed. Alerts are shown whenever these bounds are crossed by the ratio.

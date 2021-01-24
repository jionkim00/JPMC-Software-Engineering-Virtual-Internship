# Task 2: Use JPMorgan Chase frameworks and tools
Implement the Perspective open source code in preparation for data visualization

## Background Info:
Typically, traders monitor stock prices and trading strategies by having data displayed visually on their screens in chart form. Often these charts will be accompanied by alerts that notify users when certain events occur or when preset price thresholds are hit.

JPMorgan Chase created the Perspective tool over many years to allows users to present and manipulate data feeds visually in web applications.

Utilize the Perspective tool and make changes in the source typescripts in order to keep a continous feed of data streaming into the web application.

## Tasks Completed:
* Changed Graph.tsx to feed a continous stream of data from the datafeed/server3.py into the web app by creating intervals at which the graph can process data.
* Changed App.tsx to implement the changes made in Graph.tsx (tweaked interface IState to have the boolean property showGraph)
* Outcome: The graph displayed in the client-side web application is now a continuously updating line graph whose y axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph is now the result of continuous requests and responses to and from the server for the stock data.
* Outcome: Able to aggregate duplicated data retrieved from the server.

![Result](result_task2.png)

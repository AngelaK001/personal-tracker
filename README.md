# personal-tracker
Weight/runs/other data
## Details
1. How would you describe the inputs of your app? 
  * What goes in? What data does your app take in from the user, if any? Will it get data from a database or from a third-party service?
    * App takes in at least 2 types of data: weight recorded in Fitbit app as well as Health data from Apple app (cycle and running minutes)
2. How would you describe the outputs or possible outcomes of your app? 
  * Based on those inputs, what does the app display to the user? What are some of the outcomes or results that your app produces based on how the user interacts with it?
    * App displays a graph of weight over time along with cycle data as different color data
    * App displays a second line with running duration
    * App displays current weight in relation to goal
    * App outputs potential goal date based on prior 4 weeks of change
3. What would you store as variables in your JavaScript file for the first prototype of your app? 
  * What does the computer need to remember between when the user starts the app and when they close the page?*
    * Goal weight
    * How many weeks to take into account a pattern for the future
4. Which kinds of data types are these inputs/variables? 
  * Are they strings of text? Numbers? Boolean values (true or false)?
    * Numbers - weight, goal weight, running duration/miles
    * Boolean values - whether on cycle or not

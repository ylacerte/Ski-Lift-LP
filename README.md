# Ski-Lift-LP

A ski resort can be modeled as a min-cost max-flow network problem. The goal is to maximize skier movement while minimizing costs (e.g. wait time, time on lift) to the skiers.

Suppose I have a certain number of skiers arriving per hour in the parking lot (supply node). Skiers move from the parking lot to one of 4 lifts. Each lift is different in terms of speed, and where it goes. Each lift has a capacity (e.g. how many skiers the lift can accommodate) and a cost (e.g. wait time and lift time).

The top of the mountain has a demand, which represents the desired number of skiers at the resort.

The quest is to find the best lift utilization that is cheapest overall, and maximizes the flow of skiers at the resort. 

A Linear Program (LP) model is formulated and solve in a R shiny application.

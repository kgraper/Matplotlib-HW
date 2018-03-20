# Matplotlib-HW

I chose to do the Pyber Challenge. I chose to separate the data by type of city first, and then find the required figures.
The challenging part I found was how to get the driver_count column to not have repeated data. I ended up using the drop_duplicates method.
This allowed me to have unique entries for each city based on type of city, rides, drivers, and fares.
Next, I converted the unique findings into DataFrames so that I could form a scatter plot.
After that I moved on to the Pie Charts.
For those I used .loc to find the specific values specified by city type to then find totals and percentages.
In hindsight I would have liked to have found a way to use the method I used above and not had to do .loc 3 times for each pie graph.

Matplotlib Homework Observable Trends

1.) The Urban city type has the most drivers and by having the most drivers, they have the lowest average fare.

2.) In contrast, the Rural city type has the least amount of drivers and therefore the highest average fare.

These two trends are the basis of supply and demand. ie.. Rural drivers may be able to make more money per trip but they will have 
less trips.

3.) Suburban trips make up 27% of total rides while they account for 31% of the total fares. Therefore, suburban drivers are probably paid
the best per trip.

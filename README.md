# The Challenge: Finding the Perfect Spot
Imagine driving an EV across Germany’s highways with few places to charge. While city charging is more accessible, long-distance travel presents a challenge. Our task was to predict the high-utilization locations for fast chargers, focusing on highways where rapid charging is essential for drivers.

# The Approach
We combined four years of charging data from E.ON with external datasets (traffic flow, gas stations, vehicle density). Our approach followed these key steps:
Understand the Problem: EV drivers need fast, reliable charging on highways. We focused on DC fast chargers for long-distance travel.
Enrich the Data: We added traffic data and gas station locations, looking for high-traffic areas and existing infrastructure.
Model Building: We used machine learning models like Random Forest Regressor to predict charger utilization, selecting gas stations as ideal spots.
Strategic Placement: Inspired by fast-food chains, we targeted gas stations—locations already visible, accessible, and equipped with infrastructure.

# The Results
Our final model selected 1,000 high-potential locations for new charging stations, optimizing for high utilization, driver convenience, and existing infrastructure. These locations are spread across major highways and high-traffic areas.

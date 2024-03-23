## Mapping Severe Weather Events

I aim to enhance the understanding of the spatial distribution and impacts of storm events across the United States by utilizing data from NOAA's National Centers for Environmental Information (NCEI), which maintains comprehensive records of all severe storm occurrences. Through analyzing this dataset, I seek to create visual representations that elucidate patterns and trends within these events.

My analysis includes:
1. Damage from Storms
- Generate a static state-level choropleth map of the United States visualizing where monetary damage is recorded.
- Generate a static county-level choropleth map of the United States visualizing where monetary damage is recorded.
- Generate a density map to highlight the density of severe events by focusing on the variables of injuries and deaths associated with storms.

2. Location of Severe Events
- Generate a leaflet map of the United States showing the location of severe weather events that result in at least one death.
- Start with the previous map. Distinguish the markers of the weather event locations by EVENT_TYPE. Choose an appropriate coloring scheme to map the locations by type of weather event. Add a legend informing the user about the color scheme.
- Add marker clustering, so that zooming in will reveal the individual locations but the zoomed out map only shows the clusters. 

3. Severe Events and Cities
- For all severe weather event locations, identify the nearest city among the Top 100 largest cities in the United States and calculate the distance between the weather event location and the storm location.
- Provide a scatter plot showing the relationship between weather event impact and city population.
-  Visualize the patterns separately for different type of weather events.

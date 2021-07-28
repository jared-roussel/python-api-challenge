
# python-api-challenge

Analysis: This assignment required us to randomly select 500+ cities based upon latitude and longitude. Citipy was then used to find the nearest city to these coordinates. The open weather API was utilized to find pertinent weather details about each city. Additionally, the Google Places API was utilized to find the nearest hotel for cities with "perfect" weather.

The weather data is plotted based upon latitude values and displayed in the graphs within WeatherPy.inybn. The VacationPy.inybn file contains 2 heatmaps -- one with the relative humidity near each city and the other with location markers for the hotels nearest each city.

Observations:
1. There is a clear correlation between latitude values and max temperatures. For the scatter plot of latitude vs. max temperature, the plot arches and most values peak for coordinates near 20 degrees N latitude. The plot indicates there is higher correlation for the Northern Hemisphere versus the Southern Hemisphere. 
2. Overall, the Northern Hemisphere appears to have more clustered data than the Southern Hemisphere. Since the selection of original coordinates was random, this may indicate that most cities are in the Northern Hemisphere. The observation for the clustering is observed across all scatter plots, including the plots that are split by hemisphere. The Northern Hemisphere plots show tighter coorelation between latitude and all weather metrics.
3. The heatmaps indicate the perfect weather (as defined) is located near the Mediterranean Sea. The filtered and cleaned dataframe for perfect weather conditions narrowed down the list of 500+ to just 15 cities and hotels near the Mediterranean Sea.
![Heat map with markers](https://user-images.githubusercontent.com/84818223/127268654-afb08417-024e-4fe5-aee1-b6b814656eaf.PNG)
![heat map without markers](https://user-images.githubusercontent.com/84818223/127268680-84e09609-d3ea-416b-9bfc-c0f57b4dbc9d.PNG)




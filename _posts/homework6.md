Visualization 1: Horizontal Bar Chart of Unique Building Locations by City
For this visualization, I created a horizontal bar chart using Altair to show the top 20 cities with the highest number of unique building locations. The y-axis represents the city names, while the x-axis shows the count of unique buildings. To make the visualization clearer and more readable, I chose a horizontal layout to avoid clustering and overlapping of city names. The bar colors use a sequential "blues" color scheme, encoding the count of unique buildings. This choice emphasizes higher counts with darker shades, making it easy to compare the cities.

On the analysis side, I transformed the data by grouping it by city, counting the unique building locations for each city, and sorting them in descending order. The dataset was then filtered to display only the top 20 cities. While this plot does not include interactivity, it provides a clear static view of the data distribution.

Visualization 2: Interactive Geographic Map of Building Locations
The second visualization is an interactive map created using Altair to show the geographic distribution of building locations. Each point on the map corresponds to a unique building, plotted using its latitude and longitude. The points are color-coded by building status (e.g., "In Use" or "Vacant") using a categorical color scheme. This encoding highlights the status differences across locations.

I applied data transformations to filter out entries with missing latitude/longitude values and ensured that the building statuses were properly categorized. For interactivity, I added tooltips that display the building name, city, and status when hovering over a point. This interactivity enhances user engagement and allows for detailed exploration of the dataset, making it easier to identify patterns and outliers.

Discussion of Interactivity
The second plot includes hover-based interactivity, which allows users to explore specific details about each building without overwhelming the visualization with text. This interactivity makes the map more engaging and informative, especially when dealing with a large number of data points.

### Links

- [The Data]([https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv])
- [The Analysis]([https://github.com/your_username/your_repo/blob/main/Workbook.ipynb])

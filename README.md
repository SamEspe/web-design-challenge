# web-design-challenge

## Contributor: Sam Espe

### Overview

This is my submission for Homework #11 for Data Science Bootcamp. The goal of this project was to use Bootstrap, CSS, and HTML to create a website to display the results of WeatherPy from homework #6. In the `Resources` folder, there is a `CSV_to_HTML_Conversion.ipynb` Jupyter Notebook, `cities.csv`, and `cities.html`. In the `assets` folder, there are two sub-folders: `css` and `images`. These sub-folders contain the CSS stylesheet for the website and the graph images, respectively. In the `visualizations` folder, there are the HTML files for each of the four plot pages.

#### Creating the Graph Images and HTML Table
We were provide the data for the cities as a CSV file, and I used that data to create a dataframe using Pandas in a Jupyter Notebook from which I could create my graph images for the webpage. I also used the Jupyter Notebook to export the CSV file of city weather data to an HTML table. 

#### The Website
The Home page displays all 4 graph images and a short description of the project. The Comparisons page displays the graphs on the same screen; when one clicks on a graph, it links to that graph's visualization page which has a short summary of what the graph shows. The Data page displays a table of the data used in the project. Each line in the table represents the data obtained from OpenWeatherAPI about a city: the city_id (an arbitrary index), the city's name, the cloudiness (%), the country the city is located in, the date the measurement was taken, the humidity (relative % humidity), the city's latitude, the city's longitude, the maximum temperature measured that day (degrees Fahrenheit), and the wind speed (in miles per hour).

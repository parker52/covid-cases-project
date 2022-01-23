# covid-cases-project

## A Jupyter Notebook that pulls Johns Hopkins COVID-19 case data and visualizes trends for a specified county and date range 
The goal is the project was to become more familiar with manipulatig large datasets, visualizing data with matplotlib, and building functions that take user input.  

- Data Source: https://github.com/CSSEGISandData
<br></br>

### Libraries Used:
- pandas
- matplotlib
<br></br>

### function *graph_county*
reads data from Johns Hopkins, cleans and formats the data, and visualizes the data using matplotlib.
<br></br>

### function *show_graph*
allows the user to input the following parameters for the visualization: 
- state: the state that the user would like to visualize
- county: the county that the user would like to visualize 
- num_days: the number of days to visualize (e.g. an input of "30" will look at the previous 30 days)

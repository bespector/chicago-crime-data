# Analyzing Chicago Crime Data 

Just some fun scripts to download and plot data from the City of Chicago. Data and API available at https://dev.socrata.com/foundry/data.cityofchicago.org/6zsd-86xi

This notebook has been tested/requires the following packages:

  - Python 2.7
  - bokeh 0.12.13
  - [sodapy](https://github.com/xmunoz/sodapy)
  - pandas 0.20.1
  - matplotlib 2.0.2  

You may need to open your jupyter_notebook_config.py and edit c.NotebookApp.iopub_data_rate_limit to display all the graphs:
  

## Scatter plot of longitude/latitudes where crimes occured
![Alt text](/images/CrimeScatterPlot.PNG "Map of Chicago")

## Monthly Crimes:
![Alt text](/images/MonthlyCrimes.PNG "Monthly Crimes")

## K-means clustering on Narcotics data:
![Alt text](/images/NarcoticsCrimeClusters.PNG "Narcotics")


# Covid-vaccination-status-analysis
Analyze covid cases amongst vaccinated and unvaccinated people over time


The csv file used is from the OpenCovid.ca project. 
https://github.com/ccodwg/Covid19CanadaArchive#data-catalogue
The purpose of that project is to provide a backup for all datasets regarding the pandemic that were published by governmental and non-governmental sources.


The purpose of this project is to analyze specific datasets from the source above and answer the question:
Is there any difference in covid-positivity rates amongst the vaccinated, partially vaccinated and the unvaccinated in Ontario?


How to run:
dataPlot.py can be run with the following command : python dataPlot.py dataUpdates/hospitalizations-and-cases-by-vaccination-status.csv plot.pdf
There are two command line arguments: the first one being the location/name of the datafile to read and the second one being the name of the plot that will be created.

The answer to the question above can be obtained by analyzing the data using various plots, and the code can be tweaked easily to do just that.

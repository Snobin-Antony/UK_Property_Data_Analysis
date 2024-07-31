# UK_Property_Data_Analysis
This repository contains data analysis and visualization tasks focused on the UK property market, utilizing Land Registry records and other relevant datasets. The analysis includes identifying potential data entry errors, calculating key statistics, and visualizing data trends across different regions and property types. The repository aims to provide insights into property sales, price distributions, and regional variations, using a combination of statistical and geospatial methods. Additionally, it explores how to integrate Energy Performance Certificates (EPCs) with property transaction data to enrich the analysis of sale prices.

The exercise aimed to familiarize with big datasets, adaptability in working with property insight, and comfort with applying statistical techniques to manipulate data. The dataset is approx 10GB of data files, the sources for which are provided below. 

Land Registry:- https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads
Postcodes (NSPL):- https://geoportal.statistics.gov.uk/datasets/f7464f3658ba439ba577651b32014cfe/about
British National Grid shapefiles:- https://github.com/charlesroper/OSGB_Grids?tab=readme-ov-file

## Exercises 
Using the sources above: 
1. Find two land registry records that are likely to be errors. In each case, provide a potential explanation 
2. Create a table by calculating the number of sales and average sale price for all London Boroughs in 2023.
3. Count the number of new build Flats sold in each UK region since the start of 2020.
4. Plot the number of sales per week since the start of 2020 as a line chart Discuss the chart, and provide potential explanations for any patterns or anomalies.
5. Plot a histogram of sale prices and discuss which distribution best represents the data Feel free to transform the data before plotting, and explain the reasoning of chosen transform.
6. Using the BNG tiles and an appropriate scale, plot a map showing the number of sales per 10km grid square.
7. Plot a map showing the average sale price per 10km grid square.
8. Discuss: Given everything you have learned from the exercises above, discuss the following model. In your discussion, provide an approximate R square value that you would expect from the model. How would you improve the model? What range of R square value would you be happy with?
9. Discuss: Energy Performance Certificates (EPCs) are published for each property transaction recorded by the Land Registry. The data schema for these is available here https://epc.opendatacommunities.org/docs/guidance#glossary. Which fields from this dataset would be useful in determining sale price? How would you approach the task of joining the EPC database with the Land Registry?


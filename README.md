### Team Name: Dissolvable Data

### Team Members: 	
Andy Oh  
Sean Slavin  
Baskaran Viswanathan  

**Date:** 9/21/2017 

### Proposal: 
We will dissolve all the data to find a list of recommended suitable cities to place a headquarter/branch of any company based on its specific parameters. 

Our data will be retrieved from U.S. Census Bureau, Bureau of Labor Statistics, and Google Maps. We will develop an algorithm that will determine the best suitable cities by analyzing various parameters such as population size, proximity to population center, proximity to major airport, access to public transportation, labor force, cost of living, density of company type (competition) in a city, and the cultural diversity. 

### Process: 
We have downloaded a database for city population from the U.S. Census Bureau. We will use a minimum population filter (taken from a user input) to retrieve our initial list of potential cities, based on this database. We have also pulled labor force data from the Bureau of Labor and Statistics (BLS). This will provide us with information of how many employees of a particular industry/occupation in each Metropolitan Statistical Area (MSA) in the country. After matching our city to its corresponding MSA, we will record the size of the labor pool for the company’s industry type (another user input) within each of the cities in our filter. After that, we will evaluate location factors of the cities, using the Google Maps API. We will record things like density of the company type and proximity to major airports for each city. Each of the factors we evaluate will be given a score. These scores will be weighted to give us an overall score, based on our algorithm. We will then provide an output of the top cities for the given company, and provide visualizations that show how the cities scored in particular categories.

### Resource: 
[U.S. Census Bureau](https://www.census.gov/)     
[U.S. Census Bureau FactFinder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml)  
[U.S. Census MSA Data](https://www.census.gov/geographies/reference-files/time-series/demo/metro-micro/delineation-files.html)  
[Bureau of Labor Statistics](https://www.bls.gov/)  
[BLS Labor Force by Occupation Data](https://www.bls.gov/oes/tables.htm)
[Airports](http://ourairports.com/data/)  
[Google Maps API - Distance Matrix](https://developers.google.com/maps/documentation/distance-matrix/)  
[Python Inquirer](https://pypi.python.org/pypi/inquirer)  

### Project Links: 
GitHub - https://github.com/TurnpikeWarrior/Project_DissolvableData
YouTube - https://youtu.be/o_ya8Bv0BLw  
Jupyter Notebook - https://github.com/TurnpikeWarrior/Project_DissolvableData/blob/master/DissolvableData_Solution.ipynb
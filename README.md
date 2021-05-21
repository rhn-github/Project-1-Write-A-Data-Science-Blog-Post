# Project-1-Write-A-Data-Science-Blog-Post
Repository for Project Number 1 in the Udacity Data Science Course

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Sourced Data](#data)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python; with
* numpy
* pandas
* matplotlib.pyplot
* matplotlib.style
* matplotlib.patches 
* seaborn
* collections

being used


The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using the latest availabe AirBnB data for the cities of Boston and Seattle from insideairbnb.com to better understand:

1. How much does one person have to pay for the entire apartment, private room, and shared room in each community? 
2. Does advertising the accessibility of the property (i.e is there Parking, vicinity to public transportation or the airport) relate to number of ratings or price?
3. How do the prices compare between the cities of Boston and Seattle in general?

## Sourced Data <a name="data"></a>

* The data for this project was sourced from http://insideairbnb.com/get-the-data.html as follows:

### Seattle, Washington, United States

* `listings.csv` downloaded and saved as 'listings_seattle.csv'.

* This is a csv file containing summary information and metrics for listings in Seattle, and was created on 18 March, 2021.

### Boston, Massachusetts, United States

* `listings.csv` downloaded and saved as 'listings_boston.csv'.

* This is a csv file containing summary information and metrics for listings in Boston, and was created on 20 April, 2021


## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells and #Comments were used to assist in walking through the thought process for individual steps.  

#### 1. `neighbourhoods.ipynb` 

* It was found that the description / grouping of entries into neighbourhoods in the Boston Data differed from that in the Seattle Data. 
* This notebook was written to examine how the neighbourhood data for each City could be organised to make analysis more comparable.

#### 2. `accessibilty.ipynb`

* Whilst there is no specific column to indicate accessibilty in terms of parking, proximity to public transportation, or proximity to an airport, the information in the `name` columns mentions these in certain instances.
* This notebook was written to identify which entries contained such references, and to create columns that show if the entry is advertised as having parking, being near to public transportation or being near to the airport
* The results from this notebook were saved as .csv files and then merged with the sourced data files in the main notebook.
* Since the .csv files `boston_access.csv` and `seattle_access.csv` have already been saved with the submission, the write to *.csv code has been commented out.

#### 3. `boston_analysis.ipynb` & `seattle_analysis.ipynb`

* these are the main notebooks which were used to carry out the main analysis for the project.

## Results<a name="results"></a>

The main findings of the code can be found at the post [here](https://richard-needham.medium.com/airbnb-comparisons-ee42d6dc2ea2) available .

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to insideairbnb.com for the data.  
You can find the Licensing for the data and other descriptive information at the links  [here](http://insideairbnb.com/get-the-data.html)
Disclaimers are [here](http://insideairbnb.com/about.html#disclaimersa).  

Addition inforation regarding public transportation in the two cities was researched [here](https://www.mbta.com/) for Boston and [here](https://www.seattle.gov/transportation/getting-around/transit) for Seattle.

Images:

from [here](http://insideairbnb.com/about.html)

and [here](https://commons.wikimedia.org/wiki/File:Airbnb_Logo_B%C3%A9lo.svg)

Otherwise, feel free to use the code here as you would like! 

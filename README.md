
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Make sure to meet the requirements as stated in the requirements.txt file

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using INSEE data (french institute for statistical studies) to better understand the following:

1. Are there some particular patterns in term of salaries distribution within the country ?
2. Are there any noticeable differences salary-wise between women and men looking at geography, age, or job categories ?
3. How true is the good-old french motto "Liberty, Equality and Fraternity" , at least looking at the Equality principle with regard to salary at least?

## File Descriptions <a name="files"></a>

There is 1 jupyter noteboob available here to store analysis work related to the questions highlighted above. The notebook's name is INSEE.ipynb
Apart from the notebook, there are two distinct set of data files coming from two separated sources, not all the files were used in this analysis :

1) INSEE statistical datasets

- base_etablissement_par_tranche_effectif.csv	main dataset for firms information in France
- communes.geojson	Not used
- departements.geojson	Not used
- name_geographic_information.csv	not used
- net_salary_per_town_categories.csv	main dataset for salaries information per french cities

2) Geographical Information systems datasets used by geopandas python module

X = 1 to 5, where each value of X represents the administrative level at which the map of France is plotted (Country level , Region level , Departement level , cities level etc)
For this analysis, I used the "departement" level, so X = 2

- FRA_admX.cpg	
- FRA_admX.csv	
- FRA_admX.dbf	
- FRA_admX.prj	
- FRA_admX.shp

## Results<a name="results"></a>

The main findings of the code can be found at the Medium post available [here](https://medium.com/@andre.dourson/an-analysis-on-french-salaries-liberty-in-equality-fraternity-ca2132a6e549).



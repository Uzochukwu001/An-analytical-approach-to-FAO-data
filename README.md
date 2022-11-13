# An-analytical-approach-to-FAO-data


## A look at the Food Production Stats in Afghanistan.


This is a project using a dataset of about 59 years of FAO data from Kaggle(Get the complete datasets from https://www.kaggle.com/datasets/raghavramasamy/crop-statistics-fao-all-countries). The aim was to evaluate the total crops produced, the respective population, and their correlation to different production metrics (harvested areas, yields, and productions) for each year different countries. It was a huge challenge for me too as I did not have all the information I needed for the analysis which made me to filter in only Islamic Emirate of Afghanistan. Below is an overview of the steps taken and snapshots of the project reports.


### OVERVIEW OF STEPS TAKEN.

- Listed the different objectives and their underlying requirements.

- Cleaned the dataset using Power Query on Power BI accordingly
 
- Transforemd the datasset into a more comprehensible partner.

- Created a relational model of all necessary tables including DAX measures and derived columns.

- And finally, produced and formatted the right visuals according to the specified objectives.

- Laid out the report pages; with a navigation arrow(s) at the topmost part of each page and a date slicer on the second page (which on a filter, synchs with related  pages)



### Below are the screenshots as obatined from the dataset.




![Github FAO 1](https://user-images.githubusercontent.com/112668327/201503454-557cf5fc-52bc-418e-a7ee-357ff2c1e96a.png)




- The above picture shows an overview of Aghanistan as a country in terms of capital, flag and official languge. It has a navigation arrow at the top right for moving on to the next report page as well as a static design of an imaginary FAO webpage.




![Github FAO 2](https://user-images.githubusercontent.com/112668327/201503475-8c509da1-975b-4c02-a22e-29e795bb595d.png)




- The above picture shows the total number of crops grown in Afghanistan and the total population (male vs female) from 1961 till 2019, as card designs at the top of the report page. There are two visualisations on this report page viz; the Percentage ratio of male vs female population over the years and the Top 25 crops grown, indicating the range of harvested areas, yields and production levels over the years also. These visualisations can be filtered to get specific insights based on a timeline given by the date filter at the top right corner of the report page, which also synchronises on filter, with the following page. It has two navigation arrows at the top right/left for moving on to the preceding or following report page as well as a static design of an imaginary FAO webpage.




![Github FAO 3](https://user-images.githubusercontent.com/112668327/201503570-002c121c-e0b3-4712-8dea-2b4a92126c12.png)




- The above picture shows the total population density in Afghanistan, the harvested areas (in hectares), total yields(in tonnes) and total crops used for production(in tonnes) as card designs at the top of the report page. There are two visualisations on this report page too, viz; the Total Yields vs Total Production per population density over the years and the Total Yields vs Total Production per crop over the years also. These visualisations can be filtered in synchronization with a filter on the preceding page. It also has a navigation arrow at the top left for moving to the preceding report page as well as a static design of an imaginary FAO webpage.

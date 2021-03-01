# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference


###  Problem Statment

Traffic accidents are the main problem in the Kingdom of Saudi Arabia, which has increased over the past years in various regions, and there are also many license holders during the past years from different regions in the Kingdom of Saudi Arabia, and by knowing the percentage of license holders in each region that can be find out the number of drivers per year, knowing the rates of traffic accidents and checking them to find solutions.

---

### Datasets


For this project, I have two datasets to work with it:

[Driving Licenses](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-driving-licenses-issued-in-the-kingdom-2004-2008/information/?disjunctive.administritive_area&sort=time_period&location=5,24.37495,45.08024&basemap=jawg.streets)
This dataset contains Saudi Arabia Driving Licenses Issued By Administrative Area for 1993 - 2016. Data from General Authority for Statistics . Follow datasource.kapsarc.org for timely data to advance energy economics research.

[Traffic Accidents and Casualties](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/export/?disjunctive.region&disjunctive.indicator&sort=time_period)
This dataset contains Saudi Arabia Traffic Accidents and Casualties by Region for 2016. Data from General Authority for Statistics. Follow datasource.kapsarc.org for timely data to advance energy economics research.


---

### Deliverables

- A Jupyter notebook that describes your data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of your project.
- A blog post in Arabic or English that showcases the problem and key findings of this project. More information will be given on this.


---

### Executive Summary

In 2021, I began to analyze and study traffic accidents and driving licenses datasets in the Kingdom of Saudi Arabia in order to an exploration of the regions that record the highest rate of traffic accidents during the past years, this dataset contains data up to 2017.  The dataset was cleaned, analysis by graphs and statistical calculations were used.  I would like to find in the end of study and analyze this data to recommends some solutions to reduce accidents in Saudi Arabia.

---

### Submission


- A README.md 
- Jupyter notebook
- Data files
-A blog post Traffic accident data analysis in Saudi Arabia (https://data2021world.blogspot.com/2021/01/traffic-accident-data-analysis-in-saudi.html )

---

#### Data Dictionary

Explanation of each feature name in the Data Dictionary Entry:

#### Traffic_Accidents Dataset
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|int|Traffic_Accidents|Year of Traffic_Accidents that shows the date and chronology of when it happened| 
|**region**|object|Traffic_Accidents|The region of Traffic_Accidents shows the place of a scene in where the event area| 
|**accidents_category**|object|Traffic_Accidents|Shows a list of No. of Casualties, Injured and No. of Casualties, Dead, also shows No. of Accidents indicated with the region| 
|**no_of_accidents**|int|Traffic_Accidents|The value of Traffic_Accidents shows the sum of numbers of indicators for each region, how many indicators of the region that accident occurred| 
|**x**|float|Traffic_Accidents|Shows the X-coordinates of the geographical location|
|**y**|float|Traffic_Accidents|Shows the Y-coordinates of the geographical location||

#### Driving_Licenses Dataset
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**year**|int|Driving_Licenses|Shows the date of each number of driving licenses per administrative region|
|**Administritive_Area**|object|Driving_Licenses|It displays the administrative areas of all no.driving licenses|
|**no.driving_liceses**|int|Driving_Licenses|The number of driving licenses for each administrative area appears in each year|
|**x**|float|Driving_Licenses|Shows the X-coordinates of the geographical location|
|**y**|float|Driving_Licenses|Shows the Y-coordinates of the geographical location|

---


### Conclusions and recommendations 

Based on past data from the accident dataset, we can refer to multiple parameters, such as some issues with Data Set not all of the data appearing ,Each datasets are not clearly stated there is no day and month.  In Dataset driver's licenses, the drivers ages are not mentioned in order to find out the highest age group that causes traffic accidents.

I recommend solutions to reduce accidents in the Kingdom of Saudi Arabia, which found that Riyadh and Makkah are the highest rate of increase in traffic accidents. Through knowing the area, can be educated people about the importance of adhering to traffic instructions and modifying or closing dangerous roads and street lighting in some remote areas. In the driving test center, drivers must be trained and sensitized, and the quality of the tests provided must be ensured

---

### Refrence
* (https://eptsc.sa/index.php/ar/about-us-ar/background) 
* (https://medium.com/@vinitasilaparasetty/guide-to-defining-problem-statements-baf52219ea5b)
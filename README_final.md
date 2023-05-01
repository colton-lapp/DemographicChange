# README

--

### Understanding Urban Depopulation
##### An analysis of shrinking cities in the US with machine learning approaches 

--

### Authors

**Chi-Shiun Tsai** // *chishiut@andrew.cmu.edu* // Github: colton-lapp

**Colton Lapp** // *cglapp@andrew.cmu.edu* // Github: dcstsai

--

### Disclaimer / Sensitive Content

We would like to acknowledge that this research project includes some data on crime and COVID-19, which may have affected some individuals or communities more intensely than others. While the majority of the content in this project is suitable for most audiences, we understand that these topics may be sensitive to some readers. We would like to assure our readers that we have strived to approach this research with sensitivity and respect towards those who have been impacted by these issues. Our aim is to provide factual and informative research while acknowledging the seriousness of both crime and COVID-19, and their effects on individuals and communities.

--

### Project Description
City population has an impact on economic growth, political representation, and cultural development. Many big cities in the United States, including San Francisco, New York, Washington D.C., and Boston, experienced population loss during the pandemic, which poses challenges to policymakers due to funding gaps and the reallocation of land use. In this project, we aim to explore to what extent population change is predictable with machine learning algorithms. We classify cities as growing/shrinking depending on their population change between 2019 and 2020 and then use classification algorithms to try and predict this using data from the ACS on the city level as well as COVID case and death data from the NYTimes Covid Tracking project.  

Additionally, we are interested in looking for latent patterns across cities that may not be obvious at first. To this end, we employ several unsupervised clustering algorithms to try to detect patterns in our city wide dataset. By performing unsupervised clustering algorithms on cities, we hope to provide insights for policy makers and residents who may be looking for a list of cities that are similar along a wide variety of important demographic data. 

**Key Words** - Population Growth, Machine Learning, Clustering, Classification, Census Data, ACS Data, Covid-19, Urban Analysis

--

### Questions

1. Why did major cities experience different rates of population change during the pandemic? (target variable: population change 2019-2020)
2. What are some ways we can cluster cities into categories based on all available data, and will this reveal any geographical patterns about city development? (unsupervised learning, clustering)

--

### Data Collection

**Dataset Link:**

*Google Drive:*

 https://drive.google.com/file/d/1HvzqJBG5WATxag7b8K8PpqvJYyuxDiei/view?usp=share_link

**Backup Link:** 

*Dropbox*

https://www.dropbox.com/s/akbbq261ssdpgpu/data_all.csv?dl=0


**Census Data**

Most of our data was retrieved using the Census API through the python package "Census" (https://pypi.org/project/census/). We used this package to download census data files for every city in the United States. We then directly downloaded the corresponding shapefiles from the census website using a direct download link.

**Covid Data**

The COVID data came from the New York Times COVID Tracking Github page. (https://github.com/nytimes/covid-19-data) This data is on the county level, so we needed to perform GIS processing to merge it to our city level Census data. We performed this by intersecting county and city shapefiles and then making city COVID rates equal to the average of all intersecting counties in that city. 

**Crime Data**

We did not end up using crime data due to question/time/quality limitations, but we downloaded this from the FBI Crime Data Explorer for 2020 at the following url: https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home

### Branching Strategy

We created a branch for each question independnetly (Q1 and Q3, as we originally had a Q2 that got dropped) and whenever we were working on a certain question we were using that branch. We then pushed those commits and put in pull requests to merge them into the main branch. We used pull requests and added comments as we reviewed changes in pull requests. We used conventional commits (chor, feat, etc) and each team member followed this strategy. We used Jupyter lab git extension to reserve any merge conflicts.


## Running the Project / Getting Started

In this section, you include instructions on how to run your project. Think of them as steps. Include which notebook to run first and what each notebook contains. 

# Eren Janberk Genç's Portfolio 

**Hello there!**

Here's a page where you can find my data analysis projects. Most of these projects are projects that i've worked on in my free time, independent from my field of study.

**I hope that you'll find something that catches your interest!**

## Projects

### Making sense of my hometown Istanbul through open - source urban data
Istanbul is my hometown. I decided to base off a series of projects on this giant city so that i could contribute a little to the pool of knowledge about it. Most of the datasets that i used to conduct analysis are drawn from open source databases. The projects are published in both English and Turkish to engage a broader audience.

* * *

#### A Tribute to My Wrongness: How Health Tourism Interacts with Airbnb Rents in Istanbul ####

##### Links

- [Source Code](https://github.com/ejgenc/Data-Analysis_Istanbul-Health-Tourism)
- [Medium Article (in English)](https://ejgenc.medium.com/a-tribute-to-my-wrongness-istanbul-data-analysis-2c4f63176dc6)
- [Medium Article (in Turkish)](https://ejgenc.medium.com/istanbul-saglik-turizmi-d4ffd0694ddf)

##### What is this?

Motivated by my previous data analysis project about the distribution of health services across Istanbul, I have come up with another urban data analysis project. This time, I am looking at various datasets to see whether there is some kind of a linear or monotonic relationship in between the price of an Airbnb rental and its closeness to a health tourism institution.

##### Technical Details

This project features a few major technical improvements over the last one. **I've organized the whole analysis with reproducibility in mind.**
To ensure succesful replication, I've created a minimal packaging of the project, the environment and the steps that are needed to reproduce the analysis.
The following Python packages were used to ensure replicability:

* [**doit**](https://pydoit.org/) --> A Python build tool like _Make_ that is used to order all the scripts in a pipeline fashion.
* [**pytest**](https://docs.pytest.org/en/stable/) --> Used in unit testing helper functions and doing data quality testing on intermediate datasets.

The geospatial analysis portion of the project is done with the help of the following packages:

* [**GeoPandas**](https://geopandas.org/) --> Pandas for geospatial data, supports metadata such as CRS.
* [**Shapely**](https://shapely.readthedocs.io/en/stable/manual.html) --> A Python package that handles geometric objects such as points and polygons.
* [**Geopy**](https://geopy.readthedocs.io/en/stable/) --> A Python package for GIS operations such as geocoding and distance calculation.
* [**Contextily**](https://github.com/geopandas/contextily) --> A Python package that provides basemap functionality.

Packages such as **Selenium, Numpy, Pandas, Matplotlib and Seaborn** were also used in the scraping, the processing, the analysis and the visualization of the data.

* * *

#### An Exercise in Open Data: Mapping Istanbul's Health Services

##### Links

- [Primary Dataset Source](https://data.ibb.gov.tr/en/dataset/istanbul-saglik-kurum-ve-kuruluslari-verisi)
- [Source Code](https://github.com/ejgenc/Data-Analysis_Istanbul-Health-Services-Map)
- [Medium Article (in English)](https://towardsdatascience.com/an-exercise-in-open-data-mapping-istanbuls-health-services-df145375dc4e)
- [Medium Article (in Turkish)](https://medium.com/@ejgenc/i%CC%87stanbulun-sa%C4%9Fl%C4%B1k-hizmetlerini-haritalamak-bir-a%C3%A7%C4%B1k-veri-egzersizi-9fc21a2ce049)

##### What is this?

This is a short project that aims to reveal some interesting patterns or possible inequalities regarding the distribution of health services in my home city Istanbul. It also serves as a hands-on project where I get to exercise my data manipulation and visualization skills in Python.

##### Technical Details

This project makes use of open data and open data only.

  •	Data about healthcare service providers comes from Istanbul Metropolitan Municipality’s Open Data service.

  •	The geospatial data that made mapping possible comes from the OpenStreetMap database.

This project was done using Python from end to end.

  •	The data cleaning and analysis part relies on the Pandas package. I have done considerable amounts of cleaning and pre-processing to shape the data into a format that was easier to work with.

  •	Visualizations are done in pure Matplotlib without the help of extra packages like Seaborn. I did this as a challenge to exercise my Matplotlib skills and to learn the package in deeper detail.

  •	For geospatial data, I have used the Geopandas package which is built on top of Pandas.

* * *

#### A Look Into Istanbul Metropolitan Municipality's Solid Waste Data

##### Links
- [Dataset Source](https://data.ibb.gov.tr/dataset/ilce-yil-ve-atik-turu-bazinda-atik-miktari)
- [Medium Article (in English)](https://medium.com/@ejgenc/a-view-into-istanbuls-greenness-istanbul-metropolitan-municipality-solid-waste-data-525ba89bb82a)
- [Medium Article (in Turkish)](https://medium.com/@ejgenc/ibbopendataturkish-464a22d27873)
- [Tableau Dashboard (in English)](https://public.tableau.com/profile/eren.janberk.gen.5075#!/vizhome/AviewintoIstanbulsgreenness-Dashboard/Dashboard)
- [Tableau Dashboard (in Turkish)](https://public.tableau.com/profile/eren.janberk.gen.5075#!/vizhome/stanbulunyeilliinebirbak-Dashboard/Dashboard-TR)

##### What is this?

In this project, i visualized a dataset provided by the Istanbul Metropolitan Municipality Open Data Platform using Tableau. I tried to create an overarching story about the environmental problems faced by my hometown Istanbul.

##### Technical Details

The data required minimal cleaning which was done through the Python package Pandas. I have used the Tableau software to produce the visualizations.

* * *
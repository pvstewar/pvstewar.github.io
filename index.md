# Portfolio
---
## [Analyzing Community Solar Energy Sites](https://github.com/pvstewar/Community_Solar)

<img src="/images/com_solar.png" width="400"/><br>
*(Indiana high priority community solar locations (blue), Energy Communities (yellow), and DAC Census Tracts (red))*

The community solar concept is based on the idea of building solar generation systems that can share energy generated among the site owner and community members who have significant financial need. For this project, our team from Indiana University was given the opportunity to work with a local greenbank start up organization to help identify potential sites that met a list of criteria as required to receive public funds. We were able to use publicly available datasets to find nonprofit organization in Indiana who met all of the following criteria:

1. Located within the census tract listed under the US Department of Energy Disadvantaged Communities list. These census tracts are designated to have a combination of economic need and energy vulnerability that make them preferred targets for community solar with the goal of providing more cost effective and reliable access to energy.
2. Located within specific communities that are designated as Energy Communities by the US government under an initiative focused on creating green energy jobs in communities that are affected by the fossil fuel economic sector.
3. Classified by the types of electrical service providers in order to determine the relative likelihood of success for the project based on knowledge of the ability to launch community solar projects in various service territories.
4. The overall viability of the site for solar energy projects as determined by the Google Solar API which provides various data about buildings and solar energy potential.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/Google_Maps_API-white?logo=Google)](#) [![](https://img.shields.io/badge/GeoPandas-blue?logo=geopandas)](#)

##### [Project Notebook](https://colab.research.google.com/drive/1B14NA0SVLDeGAkjkeHW4QharoPGIyFkA)
##### [Project Slides](https://github.com/pvstewar/Community_Solar/blob/main/Community_Solar_Adoption.pdf)

---
## [Creating a Scalable Data Storage System for a large Network Monitoring Application](https://github.com/pvstewar/Network_monitoring_scalable_data_store)

<img src="/images/data_model.jpg" width="400"/>

<p float="left">
  <img src="/images/snort.jpg" width="200"/>
  <img src="/images/network_diag.jpg" width="200"/><br>
</p>
*(Top: Diagram showing data flow of proposed system, Lower left: Snort packet flow output, Lower right: Network diagram example)*

This project focuses on Cybersecurity Data management with a large-scale open-source network monitoring system. Many useful open-source tools are currently available to gather data on a network in a variety of different ways. The main objective here is to examine some of the data available and to explore some of the distributed computing resources available to create a scalable distributed data storage system to gather data from multiple network monitoring endpoints. Three methods were explored, illuminating the limitations of different approaches and concluding that the most promising approach for a production system would utilize a Spark distributed dataframe as the main data store. The project then integrates complex sample data and proposes architectures for this approach.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/PySpark-white?logo=apachespark)](#) [![](https://img.shields.io/badge/MongoDB-blue?logo=MongoDB)](#)

##### [Project Notebook](https://github.com/pvstewar/Network_monitoring_scalable_data_store/blob/main/Network_monitoring_scalable.ipynb)

---

## [Clustering and Mapping Food Deserts with Venue Data](https://github.com/pvstewar/Food-Availability-Mapping)

<img src="/images/food_desert_heat_map.jpg?raw=true"/><br>
*(Heat map showing the density of food retailers in the city of Indianapolis)*

This project was created to explore the concept of "Food Deserts", or areas in a city that have limited access to healthy food sources. This project uses the Four-Square venue application's open data combined with geographic location info. The project was intended to visualize the geographic distribution of grocery stores in the city of Indianapolis, Indiana and map this distribution for easy visualization in a heat map configuration. The project can easily be adapted to map any US location. The project also uses KNN clustering to organize the zip codes around Indianapolis based on this distribution, as well as conducting some basic EDA around connections between income and food availability to help add context to the data.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/Foursquare-red?logo=foursquare)](#) [![](https://img.shields.io/badge/ScikitLearn_ML-blue?logo=scikitlearn)](#) [![](https://img.shields.io/badge/Folium-white?logo=folium)](#)

##### [Project Notebook](https://github.com/pvstewar/Food-Availability-Mapping/blob/master/Grocery%20Store%20Data%20Project.ipynb)<br>
##### [Project Report](https://github.com/pvstewar/Food-Availability-Mapping/blob/master/Grocery%20Store%20Availability%20Report.pdf)

---
## [Using Data Visualization to Examine ML and Graph Cryptocurrency Illicit Transaction Datasets](https://github.com/pvstewar/ML_Crypto_DataViz)

<img src="/images/crypt_joint_grid.jpg" width="350"/>
<img src="/images/tsne.jpg" width="350"/><br>
*(T-SNE dimensionality reduction showing multidimensional data trends in a two dimensional plot)*

The purpose of this project was to demonstrate a variety of python data visualization techniques. Given the key role of cryptocurrency in monetizing cybersecurity vulnerability exploitation, I was interested in understanding the methods used in tracking illicit transactions in some of the most common cryptocurrency types. It was challenging to find publicly available quality machine learning and advanced analytics studies that actually make their training data open and accessible, but I was able to find two projects to visualize and gain a better understanding of the data. The visualization techniques are helpful in creating more transparency around ML approaches which are typically somewhat opaque. The exploration of these datasets also helped to understand the scale and composition of the use of cryptocurrency in a variety of illicit financial activities.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/Seaborn-white?logo=seaborn)](#) [![](https://img.shields.io/badge/ScikitLearn-blue?logo=scikitlearn)](#)

##### [Project Notebook](https://github.com/pvstewar/ML_Crypto_DataViz/blob/main/ML_Crypto_DataViz.ipynb)

---

## [Loan Risk Assessment from Alternative Financial Indicators](https://github.com/pvstewar/ML_Classification_HCDR)

<img src="/images/kaggle-home-credit.jpg" width="400"/>
<p float="left">
  <img src="/images/corr_hm.jpg" width="200"/>
  <img src="/images/scatter_mat.jpg" width="200"/>
</p>
*(Top: Home Credit Organization image, Lower left: Correlation matrix, Lower right: Scatter plot matrix)*

The topic of this project is using Python Machine Learning to classify credit default risk based on data about individuals that is typically outside of the normal data reported to lenders in attempting to attain credit. The project data and the submissions included were part of the Kaggle [Home Credit Default Risk competition](https://www.kaggle.com/competitions/home-credit-default-risk). The sections of the project are divided into multiple notebooks for ease of access and can be viewed in the following links.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/PyTorch-white?logo=pytorch)](#) [![](https://img.shields.io/badge/ScikitLearn_ML-blue?logo=scikitlearn)](#)

- [Part 1 Exploratory Data Analysis](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/P1_HCDR_EDA.ipynb)
- [Part 2 Feature Engineering](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/P2_HCDR_Dataset_Build.ipynb)
- [Part 3 SKLearn Pipeline](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/P3_HCDR_ML_Pipeline.ipynb)
- [Part 4 PyTorch Pipeline](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/P4_HCDR_Pytorch_Pipeline.ipynb)
- [Part 5 Balancing with Smote](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/P5_HCDR_Balance.ipynb)

##### [Project Report](https://github.com/pvstewar/ML_Classification_HCDR/blob/main/HCDR_Report.pdf)

---

## [Gathering Business Intelligence with Web Scraping](https://github.com/pvstewar/Python_Price_Scraper_Ergo)

<img src="/images/price_change_vis.png?raw=true"/><br>
*(Varying levels of price change on tracked products)*

With this project the end user needed to keep up with changing prices in order to avoid costly pricing mistakes during a time of sporadic price increases. In this case the manufacturer Ergotron keeps their own website up to date with current suggested sale prices but does not update channel partners on this information when price changes happen. This project uses the end user supplied list of parts and can gather prices from the manufacturer's website, return those prices to an output price list CSV and visualize the price changes.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/Seaborn-red?logo=Seaborn)](#)

##### [Project Notebook](https://github.com/pvstewar/Python_Price_Scraper_Ergo/blob/master/Price%20Scarper%20Ergo_gh.ipynb)<br>

---

## [Clinical Trial Analysis](https://github.com/pvstewar/IN_Clinical_trials)

<img src="/images/US_other.jpg"/><br>
*(Map of clinical trial locations in the US)*

The purpose of this project is to gather data about clinical trials that have been conducted in the state of Indiana in order to make a determination about the level of trial activity in the state, how it compares to other states, and the nature of the trials. The goal is to understand where Indiana ranks, what areas we may be able to target to make the state more of a destination for clinic trials in the future, and to get a general sense of the distribution of trial activity across the country as a whole.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/plotly-red?logo=plotly)](#) [![](https://img.shields.io/badge/folium-white?logo=folium)](#)

##### [Project Notebook](https://colab.research.google.com/drive/1p3kx5b70l_JfLGdvxLHIDeHsae1zuaGD)<br>
##### [Project Slides](https://github.com/pvstewar/IN_Clinical_trials/blob/main/Final%20IN%20Clinical%20Trial%20Report.pdf)

---
## [Quantifying and Mapping Economic Vulnerability on a Hyperlocal Scale](https://github.com/pvstewar/Affordable_housing)

<img src="/images/IN_renters.png"/>
<img src="/images/Mon_cnty.png"/><br>
*(Top: State of Indiana econmoic vulnerablility by census tract, Bottom: Monroe County econmoic vulnerablility by census tract)*

This project was all about using Public Data to Visualize Housing Affordability by county. This project looks specifically at the state of Indiana and Monroe County but can be modified to focus on any county in the US. The goal of the project is to use publicly available data to look at the average disposable income after housing costs on a hyperlocal level. The motivation behind this project is to better contextualize the idea of economic vulnerability based on the high cost of housing in some urban areas and the need to look deeper than simply understanding the median income. This should add significant value for emergency preparedness in cities when combined with mapped data around other risk factors for natural disasters especially in resource allocation for recovery planning.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Jupyter-blue?logo=Jupyter)](#)  [![](https://img.shields.io/badge/plotly-red?logo=plotly)](#) [![](https://img.shields.io/badge/USCensus-red?logo=uscensus)](#)

##### [Monroe County Analysis Notebook](https://colab.research.google.com/drive/1QpuJQRpk4R1VypwAHDTXXkNVCmPKJWic)<br>
##### [State of Indiana Analysis Notebook](https://colab.research.google.com/drive/1dOej3ArSv2ZCYBuMJwvC1Etg4UKcnN12?usp=sharing)<br>
##### [Monroe County Housing Affordability Report](https://github.com/pvstewar/Affordable_housing/blob/main/Monroe_housing_rep.pdf)

---

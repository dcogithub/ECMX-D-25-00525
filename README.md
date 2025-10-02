Time-Series-Data-of-electricty-prices-and-PV-generation

This repository contains time series data on electricity prices and equivalent Co2 emmisions used in the paper "Environmental arbitrage with battery storage: Reducing emissions from electricity generation"							
Ángel Arcos-Vargas, David Canca, Fernando Núñez. Energy Conversion and Management X. Volume 27, July 2025, 101152. https://doi.org/10.1016/j.ecmx.2025.101152		D
<img width="734" height="63" alt="imagen" src="https://github.com/user-attachments/assets/6828fc68-f49e-46b1-ac9f-c2f25532c302" />
						
Energy Conversion and Management X							
<img width="734" height="63" alt="imagen" src="https://github.com/user-attachments/assets/e6ddd61a-0f0d-41f9-b74f-31c8de1ee60f" />
c generation over the course of a year. It also contains load and photovoltaic (PV) generation profiles obtained using univariate and multivariate time series clustering techniques. The README file provides detailed explanations of all datasets.
How to cite this project

If you use this project in your work, please cite it as:

Ángel Arcos-Vargas, David Canca, Fernando Núñez. (2025). Electricity prices and Co2 equivalent emissions Dataset (Version 1.0). https://github.com/Amiliha/Time-Series-Data-of-electricty-consumption-and-PV-generation.git
Input data for UVTS and MVTS clustering and their results

This folder contains the input time series for the execution of the Univariate Time Series (UVTS) and Multivariate Time Series (MVTS) clustering. It also contains all the results obtained by applying these clustering techniques. Together with the model explained in the article, these data allow the results presented in the article to be reproduced. The objective is to contribute to the scientific community and enable future researchers to build on this work.

Open access material: Input data for UVTS and MVTS clustering and their results

Input data for UVTS and MVTS for each season: These folders contain daily, hourly profiles of PV generation and demand. They are 24-hour time series. -MV_autumn -MV_spring -MV_summer -MV_winter

Dictionary: Each file has the same data:

Date: Date of measurement.

Day_week: Day of the week, from Monday (1) to Sunday (7).

Month: Month of the measurement.

Period: Hour of the day. For example: 1, 2, 3, ... 24

Load (kWh): measurement of the load in kWh.

PV generation (kWh): Measure of PV generation in kWh.

UVTS and MVTS clustering results: These folders contain all the results obtained using UVTS and MVTS clustering. These complete data sets allow the results presented in the article to be fully reproduced. These folders each contain the results obtained using the clustering techniques for each season of the year. The main files are the following:

-MVTS_results: -MVTS_spring: files (the same for all seasons)

    Load (kWh)_centroids.csv: Centroids of Load.

    PV generation (kWh)_centroids.csv: Centroids of PV generation.

    Distribution.csv: Distribution of the weekdays in the different clusters

    Probabilities.csv: Probability of occurrence of each cluster.

    Load (kWh)_Total_days.csv: All load profiles for this season and the name of the cluster to which they belong.

    PV generation (kWh)_Total_days.csv: All PV generation profiles for this season and the label of the cluster to which they belong.

    MVTS_spring.pdf: Figures showing all the centroids and their data.

    MVTS_spring_methods.pdf: Figures showing the results of evaluating different numbers of clusters, and comparing these with the elbow, silhouette, and own methods.

    MVTS_springLoad (kWh).pdf: Figure showing all the load centroids and daily profiles.

    MVTS_springPV generation (kWh).pdf: Figure showing all PV generation centroids and profiles for all days.

-UVTS_results:

-UVTS_springLoad (kWh): files (The same for all seasons)

total_centroids.csv: centroids of the load.

Distribution.csv: Distribution of the weekdays among the clusters.

Probabilities.csv: Probability of each cluster.

total_days.csv: All the load profiles for the season.

Load (kWh)UVTS_spring.pdf:  Figure showing all centroids and profiles for each day during the season.

metho_UVTS_springLoad (kWh).pdf: Figures showing the comparison between methods for choosing the number of clusters.

UVTS_springLoad (kWh).pdf: Figures showing each centroid and the profiles of the days that belong to it.

-UVTS_springPV generation (kWh): files (The same for all seasons)

 total_centroids.csv: centroids of the PV generation.

 Distribution.csv: Distribution of the weekdays among the clusters.

 Probabilities.csv: Probability of each cluster.

 total_days.csv: All the PV generation profiles for the season.

 PV generation (kWh)UVTS_spring.pdf:  Figure showing all centroids and profiles for each day during the season.

 metho_UVTS_springPV generation (kWh).pdf: Figures showing the comparison between methods for choosing the number of clusters.

 UVTS_springPV generation (kWh).pdf: Figures showing each centroid and the profiles of the days that belong to it.


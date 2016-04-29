#Simple Introduction

This repo contains the raw data of the paper of **Tracing road network bottleneck by data driven approach**, submmited for PLOS One. 

The data is converted to **CSV** format, thus allow to be opened at Excel, etc. 

#Formate details

The data is velocity data collected at 12/01/2012, at HangZhou city, CHINA. The meta is collected by GPS installed at each Taxi, the data in this repo is processed based on the raw data. It contains the velocity for each link at each interval (5min). For the whole day, there are 24 hours, thus 288*5min. Therefor there are 288 columns in the data.csv. Each column correspond to a 5min length time interval. 

Each row correspond to a link, labelled by its name. The two-way road is counted twice. For example, if the Link ID is 1234, Data at the two directions are collected respectively. In the dataset, there are two rows, **Link1234** and **Link1234Reverse** respectively. 

For some moments there are missing data, caused by either equipment failure, or there is no taxi go across. 
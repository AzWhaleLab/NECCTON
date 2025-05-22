# NECCTON

![image](https://github.com/user-attachments/assets/a88ea3e2-b1a9-471d-896d-e199d8d513ef)

The NECCTON project (https://neccton.eu/), funded by Horizon Europe (RIA Grant No. 101081273) and UK Research and Innovation, aims to enhance the Copernicus Marine Service (https://marine.copernicus.eu/) by providing advanced modelling products that improve support for ocean biodiversity conservation and fisheries management. These developments will contribute to a better-informed policy, management, and public awareness of marine ecosystem health.
NECCTON is currently developing 25 new or upgraded modelling products focusing on key components of the green ocean, including pelagic biogeochemistry, benthic habitats, nekton, and anthropogenic stressors. Work package 7 of the NECCTON project focuses on the modelling of higher trophic levels, including a dedicated marine mammal product.
This repository hosts the R scripts used for the development of the marine mammal product, which focuses on the long-term distribution of common and spotted dolphins within the Azores region.

NOTICE: The code is still under development and annotation is underway. It is assumed that users are familiar with statistical modelling of animal distributions.

The modelling framework include the following steps:
1.	Loading required R libraries
2.	Extracting environmental data from boat-based survey segments
3.	Preparing a prediction grid and extracting associated environmental data
4.	Performing data cleaning and exploratory analysis
5.	Fitting species distribution models (Generalized Additive Models - GAMs, Boosted Regression Trees - BRTs, and an ensemble approach based on predictive performance)
6.	Generating monthly spatial predictions for common and spotted dolphins

This code was developed by Maria Inês Pinheiro da Silva and Sergi Pérez-Jorge from the Azores Whale Lab from the Okeanos Institute of the University of the Azores (https://okeanos.uac.pt/)

![image](https://github.com/user-attachments/assets/3ffab2f1-64fa-4e05-ae46-1bea111d146c)


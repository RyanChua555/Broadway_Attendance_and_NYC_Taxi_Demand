[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/rGQRVS1B)

Download the weekly grosses and NYC theaters datasets from https://www.kaggle.com/datasets/maggieakarn/broadway-datasets and put them in data\broadway_data before running.

Download the taxi_zones folder from the tutorials and put it the data folderin before running.

Run the ipynb notebooks in this order:

Initial file downloads:
    Downloads the data files from the TLC website, referencing the code in Tutorial 1.

Preprocessing Notebook part 1:
    Geocodes NYCTheaters.csv and matches each theater to a TLC taxi zone.

Preprocessing Notebook part 2:
    Filters Yellow Taxi and FHVHV to the zones obtained from the previous notebook and filters to the date range too (2023 and 2024)

Preprocessing Notebook part 3:
    Builds the weekly Theater District, control zone, and HVFHV datasets and joins them with the Broadway grosses data.

Geospatial visualisation:
    Maps the taxi zones and theaters used in the analysis.

Analysis:
    Does the statistical analysis on the weekly datasets from preprocessing_notebook_part_3.ipynb.

Modelling:
    Builds two models to predict weekly Theater District taxi trips from Broadway attendance and calendar features: Linear Regression and Random Forest. Trained on 2023, tested on 2024.
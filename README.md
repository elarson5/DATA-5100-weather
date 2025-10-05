Comparing Rain in Seattle and Québec City 

> This project will compare precipitation in Seattle to Québec City. Utilizing data obtained from NOAA weather stations, we will determine which city receives more rain. 

---

## Project Overview


- **Objective:** The main goal of the project is to determine if it rains more in Seattle or Québec City. 
- **Domain:** Environmental/Earth Science 
- **Key Techniques:** Time Series, Data Imputation

The project used daily precipitation data from NOAA weather stations to determine if it rains more in Seattle or Québec City. It was determined that it rains more in one city depending on the season. In the winter, it tends to rain more in Seattle while in the summer it tends to rain more in Québec City.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND 
- **Description:** Data retrieved in .csv file format containing station name, date, and precipitation data. Total entries 3,431.

---

## Analysis

The project used the notebook "Weather project v4" as the final version. The project assessed the datasets for suitability of the question and changed the DATE variable to make it useable in the project. Then the two datasets were merged and missing values imputed using mean values. Finally, data was analyzed  using a descriptive approach with summary statistics and bar graphs. 

---

## Results

Summary statistics and bar graphs indicated that there is not a significant difference in number of times it rained and quantity of precipitation when viewing data daily. Viewing the data in a monthly perspective shows there is a seasonal difference in the amount it rains between Québec City and Seattle. In the winter, it tends to rain more in Seattle while in the summer it tends to rain more in Québec City.

---

## Authors

- Emily Larson - [elarson5](https://github.com/elarson5)

---

## Acknowledgements

- NOAA, Jupyter Lab
- DATA 5100 Source Material


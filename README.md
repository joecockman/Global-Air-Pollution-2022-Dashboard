# Global-Air-Pollution-2022-Dashboard

![Global Air Pollution Dashboard Preview](Global-Air-Pollution-Dashboard.png)

The purpose of this dashboard is to allow users to delve deeper into global air pollution data. The dashboard is built around a dataset downloaded from Kaggle, titled: 'Global Air Pollution Dataset 2022', which detailed that the data was sourced from elichens. This dataset file can be found above in the repository.

This dashboard allows you to see the average air quality index (AQI) of countries across the world, as well as look into specific pollutants, such as CO and NO2.

## I have included visuals on the following variables:

- Interactive world map
- Information Table
- Air Quality Gauge
- Best / Worst air quality countries

## I have also included filters on the page to help narrow your search. These include:

- Country Search Bar
- Pollutant Category Toggle

## I created the following calculated columns that are used in many of the visuals:

- Average AQI
- Average AQI Category
- CO Average AQI Category
- CO Country Average
- NO2 Average AQI Category
- NO2 Country Average
- Ozone Average AQI Category
- Ozone Country Average
- PM2.5 Average AQI Category
- PM2.5 Country Average

# Country Search Bar

average aqi numbers are calculated columns

category slicer is slicer with a field parameter of the average categories

map is location: country , legend: categories (field parameter) , tooltips: categories (fp)

best air quality: card. fields: Min average aqi, country
worst air quality: card. max average aqi, country

gauge: value: measure - selected country aqi.

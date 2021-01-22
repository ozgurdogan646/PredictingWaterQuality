# Predicting Water Quality

## Abstract
Humanity have some fundamental needs for existing and the most important of these is water. However, some people continue to pollute lakes, seas and oceans. Water pollution is mostly a result of oil spills and industrial wastes. On the other hand, studies are carried out in many areas to prevent water pollution. When we heard about the presence of algae that clean water and increase the water quality , we decided to focus on this issue. In this project, we aimed to create a model that predicts which waters needed this algae.


## Work Plan

| Action                     | Oguzhan Sahin | Ozgur Dogan | Dilara Sahan |
|----------------------------|---------------|-------------|--------------|
| Data Collection            |       x       |      x      |              |
| Data Preparation           |               |      x      |       x      |
| Data Preprocessing         |       x       |      x      |       x      |
| Data Exploration           |       x       |      x      |       x      |
| Classification Model       |       x       |             |              |
| Regressor Model            |               |             |       x      |
| Classification by Features |               |      x      |              |
| Model Comprasion           |       x       |      x      |       x      |

## Directory Structure
- Root
  - Notebooks
    - CollectData.ipynb (Collected data from WorldBank, SEDAC, Data Europa, Foursquare, OSM)
    - EDAWaterPolllutionDataFolium.ipynb (Visualized our main water pollution data with Folium)
    - PreProcessWaterPollutionData.ipynb (Prepared final data)
    - WaterPredictionModel.ipynb (Created classfication and regression models)
    - concatData.ipynb (Concatenated all external data with main data)
    - fullDataEDA.ipynb (Exploratory data analysis on final data)
  - Reports
    - PredictingWaterQualityReport.pdf
    - PredictingWaterQualityReport.tex
  - Images

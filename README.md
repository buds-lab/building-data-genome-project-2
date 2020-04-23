![logo](figures/buildingdatagenome1.png)

# Building Data Genome 2.0 Data-Set
## Data-set description
It is an open data set from 1636 non-residential buildings that includes hourly whole building data for two year, from different kind of meters: electricity, chilledwater, steam, hotwater, gas, water, irrigation and solar. Each of the buildings has metadata such as area, weather, and primary use type. This data set can be used to benchmark various statistical learning algorithms and other data science techniques. It can also be used simply as a teaching or learning tool to practice dealing with measured performance data from large numbers of non-residential buildings. The charts below illustrate the breakdown of the buildings according to primary use category and subcategory, industry and subindustry, timezon and meter type.<br>

![cat_features](figures/metadata_features.png)

## Getting Started
We recommend you download the [Anaconda Python Distribution](https://www.continuum.io/downloads) and use Jupyter to get an understanding of the data.
- Raw temporal meters data are found in `/data/meters/raw`
- Raw metadata is found in `data/metadata/`
- To join all meters raw data into one dataset follow [this](/notebooks/00_All-meters-dataset.ipynb) notebook

Example notebooks are found in `/notebooks/` -- a few good overview examples:
- [Exploratory Data Analysis of metadata](notebooks/01_EDA-metadata.ipynb)
- [Exploratory Data Analysis of weather](notebooks/02_EDA-weather.ipynb)
- [Exploratory Data Analysis of meter reading](notebooks/03_EDA-meter-reading.ipynb)

## Citation of BDG 2.0 Data-Set
* (publication)
* (ResearchGate)
* (Bibtex)

# Publications or Projects that use BDG 2.0 data-set
Please update this list if you add notebooks or R-Markdown files to the ``notebook`` folder. Naming convention is a number (for ordering), the creator's initials, and a short `-` delimited description, e.g. `1.0-jqp-initial-data-exploration`.

- (publication here)

## Repository structure
```
building-data-genome-project-2
├─ README.md              <- BDG 2.0 README for developers using this data-set
└─ data
|   ├─metadata            <- buildings metadata
|   ├─ weather            <- weather data
|   └─ meters
|       ├─ raw            <- all meter reading datasets, one file for each kind of meter
|       └─ screening      <- data-sets created during he data screening process
|           ├─ anomalies  <- all meters anomalies detected 
|           └─ breakout   <- all meters breakouts detected
├─ notebooks              <- Jupyter notebooks, named after the naming convention
└─ figures                <- figures created during exploration of BDG 2.0 Data-set
```



<!-- A repository of whole building electrical meters from non-residential buildings
============================== -->

![building data genome logo](https://raw.githubusercontent.com/buds-lab/the-building-data-genome-project/master/figures/buildingdatagenome1.png)

# Building Data Genome 2.0 Data-Set
## Data-set description
<div align="justify"></div>

(figures here)

## Getting Started
We recommend you download the [Anaconda Python Distribution](https://www.continuum.io/downloads) and use Jupyter to get an understanding of the data.
- Raw temporal and meta data are found in `/data/meters/raw`
- Raw metadata is found in `data/metadata/`

Example notebooks are found in `/notebooks/` -- a few good overview examples:
- (link EDA notebooks)

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
├─ README.md			<- BDG 2.0 README for developers using this data-set
└─ data
	├─ metadata			<- buildings metadata
	├─ weather			<-  weather data
	└─ meters 
		├─ raw			<- all meter reading datasets, one file for each kind of meter
		└─ processed	<- all meters joint in one dataset: hourly and daily
├─ notebooks			<- Jupyter notebooks, named after the naming convetion
└─ figures				<- figures created during exploration of BDG 2.0 Data-set
```



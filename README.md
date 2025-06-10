# 🌲 Forest Restoration Risk Scoring Model

## Overview
This project identifies regions at high risk of forest restoration failure based on real-world ecological, climatic, and human impact data. It uses a risk scoring model developed in Python with visualizations and insights.

## Objective
To help NGOs and policymakers prioritize areas for successful reforestation by calculating a composite risk score based on multiple environmental factors.

## Methodology
Risk is computed as a weighted sum of the following factors (all normalized):
- Deforestation Rate
- Soil Erosion Risk
- Climate Instability (temperature + precipitation)
- Human Pressure Index

Each factor contributes equally in this version of the model.

## Data Sources
- [Global Forest Watch](https://data.globalforestwatch.org/)
- [WorldClim Climate Data](https://www.worldclim.org/)
- [Open Canada - Soil Erosion](https://open.canada.ca/)
- [SEDAC Human Footprint](https://sedac.ciesin.columbia.edu/)
- [Protected Planet](https://www.protectedplanet.net/en)

## How to Run
1. Clone the repo.
2. Install the requirements.
3. Run the notebook in the `/notebooks` directory.

```bash
pip install -r requirements.txt
```

## Visuals
All outputs are stored in `/outputs` — includes heatmaps, bar charts, and spatial plots.

## License
This project is open-sourced for learning purposes. Attribution appreciated.

## Author
Akshay Tripathi

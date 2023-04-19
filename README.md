## Purpose
The notebooks/data in this repo were used to construct a dataset that was used to build a Tableau dashboard available via Tableau Public.

This is a hobby project, see `LICENSE.txt` for more information.

## Dashboard
The dashboard created from the processed data can be viewed at: https://public.tableau.com/app/profile/brown.star.kachina/viz/shared/NGM3D9N8S

![dashboard](/img/dashboard_20230418_2000.png)

The above dashboard is interactive and allows the user to drill down into more indepth geographical details across several features.

## Data
The raw data used for this project comes from [Timothy Renner](https://timothyrenner.github.io/) in his [`bfro_sightings_data`](https://data.world/timothyrenner/bfro-sightings-data) repo.

## Project structure
Below shows the tree stucture of the files for this project.
```
.
│   .gitignore
│   LICENSE.txt
│   README.md
│
├───data
│   ├───interim
│   │       add_init_raw_feats_20230416_0636.csv
│   │
│   ├───processed
│   │       processed_bigfoot_data_20230416_1539.csv
│   │
│   └───raw
│           bfro_reports_geocoded.csv
│
├───img
│       dashboard_20230418_2000.png
│
└───notebooks
        clean_raw_data.ipynb
        get_text_features.ipynb
```
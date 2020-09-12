# COVID-19 in [mybinder.org federation](https://mybinder.org/)

This repo is intended for demostration purposes and it contains:
- [data_collection.ipynb](/data_collection.ipynb): collects all launches, which contains "corona" or "covid" in `spec`, from [Binder Gallery API](https://notebooks.gesis.org/gallery/api/v1.0/) and writes them into a csv file
- [covid_binder_launches_2019_12_01_2020_09_10.csv](/covid_binder_launches_2019_12_01_2020_09_10.csv): output of `data_collection.ipynb` for the time range from 01.12.2019 to 09.10.2020 
- [analysis.ipynb](/analysis.ipynb): some analysis on the output csv file

To launch the repo:
- one-time in [GESIS Binder](https://notebooks.gesis.org/binder/): [![Binder](https://notebooks.gesis.org/binder/badge_logo.svg)](https://notebooks.gesis.org/binder/v2/gh/bitnik/covid19_in_binder/master?filepath=analysis.ipynb)
- persistently in [GESIS Hub](https://notebooks.gesis.org): [![Binder](https://notebooks.gesis.org/services/binder/badge_logo.svg)](https://notebooks.gesis.org/services/binder/v2/gh/bitnik/covid19_in_binder/master?filepath=analysis.ipynb)

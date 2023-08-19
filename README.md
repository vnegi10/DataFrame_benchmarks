## DataFrame benchmarks

This repository contains Jupyter notebooks which are
used to execute and compare DataFrame benchmarks between
[Pandas](https://pandas.pydata.org/), [Polars](https://github.com/pola-rs/polars)
and [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl) packages.

## Versions

- Python 3.10.6
    - Polars 0.17.2
    - Pandas 2.0.0

- Julia 1.8.5
    - DataFrames.jl 1.5.0

## Data source

- Hard drive [S.M.A.R.T.](http://ntfs.com/disk-monitor-smart-attributes.htm) data has been
graciously made available for public use by Backblaze. The quarterly CSV data (per day)
are bundled together into a zipped file, which can be downloaded from
[here.](https://www.backblaze.com/b2/hard-drive-test-data.html) We are making use of
data for only a selected number of days.

- Steam games recommendation data has been obtained from kaggle. More information
is available [here.](https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam?select=recommendations.csv)

- Rotten Tomatoes movies review data has been obtained from kaggle. More information
can be found [here.](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset?select=rotten_tomatoes_critic_reviews.csv)
# Formula 1 Analysis

This repository contains analysis of a [Formula 1 Dataset](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
which was done as part of a University subject. All statistics can be found in the Jupyter notebooks.

Our aim was to make a couple of experiments testing how different changes would influence the safety of the drivers and
their points in the Championships. To compute different statistics, we also computed Elo ratings for each driver from 2014 to 2024.
Even though these ratings closely reflect the skill of each driver, they should be taken with a grain of salt.
Our Elo simulation assumes that each driver have been given 1500 Elo points initially back in 2014. We then simulate all of the races
one by one and update their Elo ratings. We use a constant K of 30. Our algorithm doesn't take into account the inactivity of drivers
and doesn't use any additional momentum computations one might want to implement. Even though, the algorithm is very simple,
the maximum elo ratings computed closely reflect the general consent for the skill of each of the drivers.

### Folder Structure

The dataset files are expected to be in a folder `f1_dataset`. It is already added to the `.gitignore` file.

 - `f1_dataset`
    - `circuits.csv`
    - `constructor_results.csv`
    - `constructor_standings.csv`
    - `constructors.csv`
    - `driver_standings.csv`
    - `drivers.csv`
    - `lap_times.csv`
    - `pit_stops.csv`
    - `qualifying.csv`
    - `races.csv`
    - `results.csv`
    - `seasons.csv`
    - `sprint_results.csv`
    - `status.csv`

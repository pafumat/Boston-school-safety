# Boston School Safety Analysis

This project analyzes crime data in Boston, focusing on incidents near schools. The primary goal is to visualize and understand crime patterns to improve school safety.

## Project Overview

This project analyzes crime data in Boston, focusing on incidents near schools. The primary goal is to visualize and understand crime patterns to improve school safety.

First, the project loads the 2021, 2022 & 2023 crime reports files, which contain all the crimes reported by the Boston Police Department. Then, it loads an Excel file with the geolocation of all Boston Public Schools.

The Jupyter Notebook provided in this repository is where everything is put together. It concatenates the crime reports, filters them for the different school years, and selects only the offenses related to shootings. It also performs data cleaning and preparation.

The output of the analysis is two maps, one for the 2021-2022 school year and one for the 2022-2023 school year. The maps show the schools with a blue icon and a popup with the name of the school. The crimes are shown in red with a popup displaying the description of the crime and the date it occurred.

There is also a blue radius around each school that represents the size of two football fields to indicate the crimes that are close to the schools. Below the map, there is a widget that displays what crimes happened in which school radius, so we can see which school has had the most crimes within this radius. This allows for a comparison between the two school years.

This project provides a clear way to visualize which schools are more at risk of witnessing shooting-related crimes and also shows that it is often in more violent neighborhoods that violent crimes happen, clearly begging the question, should some schools be safer than others? Is it fair for the children to be in an environment that is less fair than others? possibly creating disparities in educational outcomes.

## Project Structure

- `data/`: Contains the raw and processed data used in the analysis.
- `notebooks/`: Jupyter notebooks for data exploration, analysis, and visualization.
- `src/`: Source code for data processing and other utilities.
- `requirements.txt`: A list of Python packages required to run this project.

## Usage

1.  Install the required packages: `pip install -r requirements.txt`
2.  Explore the notebooks in the `notebooks/` directory.
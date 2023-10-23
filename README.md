# Arizona-Fatal-Police-Shootings

## Project Description

This project was conducted during a senior statistics seminar at Hamilton College. Leveraging a dataset sourced from The Washington Post, which meticulously compiles data on fatal police shootings across the United States, the assignment tasked students with delving into the dataset to unearth intriguing relationships for further exploration.

Participants took a regional approach, dissecting the dataset to discern specific geographical correlations with shootings and crime. This particular project honed in on the state of Arizona, giving special attention to its most populous cities, including Phoenix, Tucson, and Mesa.

To enrich our analysis, we supplemented the dataset with information from policeinitiative.org, crimegrade.org, and other demographic data. This comprehensive approach provided deeper insights into the intricate dynamics between population density, geographic location, and heightened interactions with law enforcement, ultimately shedding light on fatal police shootings.

## Data Sources

- [The Washington Post](https://github.com/washingtonpost/data-police-shootings)
- [PoliceInitiatives.org](https://policeinitiatives.org/)
- [Crimegrade.org](https://crimegrade.org/drug-crimes-arizona/)

## How to Run the Code
1. Prerequisites:
   - Make sure you have R installed on your system. 
   
2. Download the Dataset:
   - Download the dataset `fatal-police-shootings-data.csv`. Place it in the directory where your R script file (`your_script.R`) is located.

3. Running the R Script:
   - Open your preferred R environment (like RStudio or any other editor).
   - Open the R script file in the R environment.
   - Select the code chunks and use the run button to execute the selected code.

4. Understanding the Script:
   - The script is divided into sections, each starting with `##` comments which indicate the purpose of that section.
   - Some parts of the code might be dependent on earlier parts being executed. Ensure you run them in order.

## Features & Technologies

### Included Data Processing

- Merging data from multiple sources.
- Aggregating sub-agencies into parent agencies for uniformity.
- Combining with population data for context.

### Key Packages
- ggplot2: for creating visualizations.
- dplyr: for data manipulation and summarization.

### Key Visualizations

- Bar plots to visualize distribution of police shootings by region and shootings by race and city.
- Line plots to visualize trends of shootings over time.
- Scatter plots to visualize crime ratings vs per capita income raings.

## Project Credits
This project was developed by the following team members: Sean Kondracki & Katie Sands

## License
This project is licensed under the MIT License.


#  Barcelona Air Quality Data Analysis Project
 
This project mainly  focuses on analyzing air quality in Barcelona which aims to identify pollution levels and understand the factors which affects air quality. This analysis covers multiple datasets, providing insights through detailed data examination and visualizations.





## Project Structure

The repository is organized as follows:
- `DATASETS/`: Contains the Barcelona air quality and supplementary datasets, including monthly air quality data, air quality station data, population data, and tree data.
- `Air Quality Project.pdf`: The comprehensive report generated from the analysis in pdf format
- `Final Project Data Tools.Rmd`:  Comprehensive Analysis of Air Quality in Barcelona in markdown Format 
- `README.md`: This file.

## DataSources

- Air quality data for each month in 2022 provided in CSV format:
  - [2022_01_Gener_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_01_Gener_qualitat_aire_BCN.csv)
  - [2022_02_Febrer_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_02_Febrer_qualitat_aire_BCN.csv)
  - [2022_03_Marc_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_03_Marc_qualitat_aire_BCN.csv)
  - [2022_04_Abril_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_04_Abril_qualitat_aire_BCN.csv)
  - [2022_05_Maig_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_05_Maig_qualitat_aire_BCN.csv)
  - [2022_06_Juny_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_06_Juny_qualitat_aire_BCN.csv)
  - [2022_07_Juliol_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_07_Juliol_qualitat_aire_BCN.csv)
  - [2022_08_Agost_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_08_Agost_qualitat_aire_BCN.csv)
  - [2022_09_Setembre_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_09_Setembre_qualitat_aire_BCN.csv)
  - [2022_10_Octubre_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_10_Octubre_qualitat_aire_BCN.csv)
  - [2022_11_Novembre_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_11_Novembre_qualitat_aire_BCN.csv)
  - [2022_12_Desembre_qualitat_aire_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_12_Desembre_qualitat_aire_BCN.csv)

- Air quality station data for 2022:
  - [2022_qualitat_aire_estacions.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/2022_qualitat_aire_estacions.csv)

- Population data for Barcelona:
  - [Barcelona_population.xlsx](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/Barcelona_population.xlsx)
  - [Barcelona_population_def.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/Barcelona_population_def.csv)
  - [Barcelona_population_def.xlsx](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/Barcelona_population_def.xlsx)

- Tree data for parks in Barcelona:
  - [OD_Arbrat_Parcs_BCN.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/OD_Arbrat_Parcs_BCN.csv)

- Geographic information:
  - [neighbourhood_size.csv](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/DATASETS/neighbourhood_size.csv)

## Analysis and Results
**The comprehensive report   generated from the analysis** 

[Air Quality Project.pdf](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/Air%20Quality%20Project.pdf)


[Final Project Data Tools.Rmd](https://github.com/Hugongra/BCN-AIR-QUALITY/blob/main/Final%20Project%20Data%20Tools.Rmd)





This project focuses on several key areas of analysis:

 ● **Data Quality**: identifying and correcting  errors found in the dataset
 
● **Average Pollution Levels**: Calculation of monthly, daily, and hourly average  of the  pollution levels.

● **Contaminant-Pollution Relationship**: Analysis of how different contaminants  contribute to overall pollution levels.

● **Geographic Analysis**: Examination of pollution levels in different neighborhoods and their correlation with the  tree density.

●**Tree Density Analysis**: Evaluation of the relationship between tree density and pollution levels.

●**Population Density Analysis**: Analysis of how population density affects the pollution levels.




## Installation

### Requirements
- R (version 4.0 or higher)
- RStudio (optional, but recommended)
- The following R packages:
  - `tidyverse`
  - `dplyr`
  - `ggplot2`
  - `readxl`
  - `rmarkdown`



## # Setup
**Clone the repository**:
```bash
   git clone git clone https://github.com/Hugongra/BCN-AIR-QUALITY.git
   cd BCN-AIR-QUALITY

 ```
**Install the required R packages;**

```bash 
install.packages(c("tidyverse", "dplyr", "ggplot2", "readr", "readxl"))
```
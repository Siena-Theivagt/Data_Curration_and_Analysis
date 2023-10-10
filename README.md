# Data_Curration_and_Analysis

# Project Description
This repository contains data and code for the analysis of survey data related to packing habits and travel preferences of survey participants. The jupyter notebook named 'Data_Curration_and_Cleaning_Software.ipynb' contains the code that cleans the survey data and turns it into the dataset, which is provided in the `travel_survey_cleaned_data-2.csv` file. This dataset is then used in the file labeled 'Packing_data_analysis_and_visualizations.ipynb', which provides descriptive statistics and  visualizations of:
- packing habits by gender
- Hours Spent Packing for Different Reasons for Travel
- Hours spent packing for different destinations
- Destination and Hours Spent Packing
- Age and gender distributions
  
### Goals
- To learn more about the packing habits of individuals, such as overpacking, underpacking, or the amount of time people spend packing.
- To find out the most common reason participants travel.

## Table of Contents

- [Dataset](#dataset)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Dataset

The dataset used for this analysis can be found in the `travel_survey_cleaned_data-2.csv` file. It includes the following columns:

- __age__: Age of the survey participant.
- __airport_spending__: The amount of money participants spent on essential travel items while at the airport or final destination in the past year.
- __gender__:The sex of the survey participant
- __packing_habbit__: overpacking or underpacking habit of the survey participant
- __travel_frequency__: frequeny
- __airport_spending__: money the survey participant spends on essential travel items while at the airport or at their 
- __reason__: the reason for why the survey participant travels
- **destination**: destination of previous trip
- __packing_hours__: The number of hours the survey participant usually spends packing their bags before a trip
- **travel_company**: the people the survey participant travels with
- __transportation_mode__: the survey participant's common or favorite mode of transportation for travel 

## Potential Issues
- Of all the survey participants, 48 are female, 13 are male, and 1 preferred not to say. So any visualizations and analyses involving the gender of participants will be biased.
- The "Reasons for Travel" data may be bias because many of the survey participants are family members of one of my teammates for the survey project.
The age distribution is skewed because we sent the survey to many college students.

## Analysis
The analysis of the survey data includes:

- Descriptive statistics to understand the characteristics of the dataset.
- Visualizations to illustrate key findings and insights.
- Code for data cleaning and analysis.

## Visualizations

We have created visualizations to provide insights into the survey data. You can find these visualizations in the [Visualizations](visualizations/) directory.

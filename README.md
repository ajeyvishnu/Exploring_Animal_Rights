# Global Animal Rights Analysis

## Overview
This repository contains the code and documentation for a comprehensive analysis of animal rights policies, practices, and perspectives across the globe. The project explores data from various countries to understand the recognition of animal rights, laws against animal cruelty, support for animal welfare declarations, and other related factors.

## Data Source
- [Animal Rights Index Data](https://data.world/makeovermonday/2024week-8-animal-rights): This dataset contains statistics from key international sources to create a comprehensive "Animal Rights Index."

## Data Dictionary
- **Country**: The name of the country.
- **Recognition of Animal Sentience (full weight)**: Acknowledgement that animals feel pleasure and pain.
- **Recognition of Animal Suffering (full weight)**: Acknowledgement that animals should not needlessly suffer.
- **Any Laws Against Animal Cruelty (full weight)**: Official laws regarding animal cruelty.
- **Fur Bans (full weight)**: Bans on fur farming or partial bans on farming furs of specific animals.
- **Support for the Universal Declaration on Animal Welfare (half weight)**: Pledged support for the Universal Declaration on Animal Welfare.
- **Meat Consumption per Capita in Kilograms (half negative weight)**: Average meat consumption per person.
- **Percentage of Terrestrial Protected Areas (half weight)**: Percentage of total land area classified as protected.
- **Kilograms of Pesticides per Hectare of Cropland (half negative weight)**: Amount of pesticides used per hectare of cropland.
- **Environmental Performance Index Score (half weight)**: A ranking of environmental health and ecosystem vitality.

## Questions Explored
1. Investigate animal rights and differences between countries through Cluster Analysis.
2. Explore the interrelationships between countries based on animal rights variables using Principal Component Analysis (PCA).
3. Identify the relationship between animal rights variables and how they can be grouped using Exploratory Factor Analysis (EFA).
4. Identify key factors underlying animal rights variables and examine relationships between countries concerning these factors.

## Analysis Highlights
- **Cluster Analysis**: Three distinct clusters were identified, aligning with countries' overall scores on the Animal Rights Index. Countries were grouped into "Progressive Protectors," "Mixed Practices Melting Pot," and "Developing Dynamics" based on their animal rights practices.
- **Principal Component Analysis (PCA)**: PCA revealed two principal components that explained a significant amount of variance in the data. Visualization of PCA results helped understand the distribution of countries based on their animal rights variables.
- **Exploratory Factor Analysis (EFA)**: EFA reduced the dimensionality of the dataset and identified two factors related to animal welfare and animal cruelty metrics. These factors provided insights into the underlying structure of the data.

## Conclusions
- The analysis showcased significant variations in animal rights practices and perspectives across countries.
- Countries with strong traditions of animal welfare and comprehensive legislation were grouped as "Progressive Protectors."
- "Mixed Practices Melting Pot" countries exhibited varying degrees of animal rights practices, influenced by cultural, historical, and socio-economic factors.
- "Developing Dynamics" countries showed a need for enhanced legislation and enforcement mechanisms to protect animal rights, reflecting challenges in resource allocation and differing cultural attitudes.
- Overall, the analysis highlighted the complexity of global animal rights issues and the importance of tailored interventions based on country-specific contexts.


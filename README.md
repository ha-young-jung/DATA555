# Opioid Overdose Mortality Data for Georgia (2020)

## Background
  - The opioid epidemic remains a major public health crisis in the United States, with significant impacts on communities across the country.
  - Over the past decade, opioid-involved deaths have steadily increased, resulting in drug overdose fatalities becoming one of the leading causes of injury-related mortality. In 2022 alone, 81,806 opioid-involved overdose deaths were reported nationwide, representing a 64% increase since 2019.2 In Georgia specifically, opioid-involved deaths totaled 1,976 in 2022, marking a more than 131% increase from 2019.
  - To effectively address this crisis, reliable small-area estimates are critical for identifying high-risk communities and ensuring efficient allocation of resources, interventions, and public health support.

## Objective
  - Examine the association between social vulnerability, socioeconomic and demographic factors, and opioid-related mortality at the county level in Georgia.
  - Estimate county-level opioid-related mortality with enhanced accuracy and reliability, and to identify counties at higher risk for opioid-related deaths.

## Methods
  - We initially fitted Poisson regression models with county-specific random intercepts, including an offset term to account for differences in population size across counties.
  - We used a Bayesian Conditional Autoregressive, or CAR model, which incorporates spatial correlation using an adjacency-based neighborhood structure so that estimates for one county can borrow strength from its neighbors. 
This helps smooth out random noise, especially in counties with small populations.

## Importance of this Project
  - By visualizing patterns in opioid-related mortality and social vulnerability, this dashboard offers insights into high-risk areas shaped by social and structural determinants of health.
# Oxford Study: Diet and Greenhouse Gas Emissions

This project analyzes the environmental impact of different diet groups (vegans, vegetarians, fish-eaters, and meat-eaters) in the United Kingdom, based on data from 2022. The study explores how dietary choices influence greenhouse gas (GHG) emissions.

## Overview
- **Tool Used**: Python
- **Dataset**: *The Environmental Impact of Vegans, Vegetarians, Fish-eaters, and Meat eaters in the UK* (2022)
- **Country**: United Kingdom

## Visualizations
- **Treemap**: Visualizes the hierarchical relationship of diet group → sex → age group, with rectangle size and color mapped to mean GHG emissions.
- **Bar Chart**: Displays the percentage of participants in each diet group across different age groups.

## Key Findings
- Meat eaters produce the highest greenhouse gas emissions.
- Vegans have the lowest greenhouse gas emissions.
- Younger individuals have a higher proportion of vegans and vegetarians compared to older individuals.
- Meat eaters are the majority in every age group.

## Data Preparation
- Related diet groups (meat, meat50, meat100) were merged into a single "Meat Eater" group.
- Data was grouped by diet group, sex, and age group to calculate mean GHG emissions.
- Another grouping was performed to determine the percentage of each diet group within age groups.
- Hierarchical structures were prepared for the treemap visualization.

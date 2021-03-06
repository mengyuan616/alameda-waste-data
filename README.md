# Alameda Waste Analysis

## Background
In this project, I hope to see how the amounts of landfilled waste in Alameda have changed over the past few years, and what have been the major types of waste generated by people and different business groups.

## Source data
I used 4 datasets from CalRecycle, the California Department of Resources Recycling and Recovery:

1. The amount of waste in all counties: https://www2.calrecycle.ca.gov/LandfillTipFees/
2. Residential waste in all counties: https://www2.calrecycle.ca.gov/WasteCharacterization/ResidentialStreams
3. Commercial waste in Alameda：https://www2.calrecycle.ca.gov/WasteCharacterization/BusinessGroupStreams
4. Waste facilities in Alameda：https://www2.calrecycle.ca.gov/SolidWaste/Site/DataExport

## Notebooks
This repo contains two notebooks:

### 01-download and clean.
I used this notebook to download and import selected columns of the 4 datasets, and exported 4 cleaned csv files.

### 02-explore and analyze.
I used this notebook to explore the data and answered 5 specific questions:

Q1: From 1990 to 2020, how many tons of garbage were landfilled in Alameda County each year?

Q2: What were the major types of waste different business groups were producing in Alameda?

Q3: What were the major types of residential waste in Alameda? 

Q4: What is the proportion of waste disposed in Alameda in the whole state？

Q5: How many waste management facilities were documented in Alameda? What's their status?

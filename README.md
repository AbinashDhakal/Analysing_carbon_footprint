# Analysing_carbon_footprint
This repository contains SQL queries and analyses for analyzing carbon footprints based on a dataset of product carbon footprints (PCFs) for various companies. PCFs are the greenhouse gas emissions attributable to a given product, measured in CO2e (carbon dioxide equivalent).

## Background
Greenhouse gas emissions attributable to products—from food to sneakers to appliances—make up more than 75% of global emissions.


## Dataset
The dataset used in this analysis is publicly available on nature.com and it stores product carbon footprints (PCFs) for various companies. The dataset contains the following fields:

id: Identification of the record
year: Year of the data
product_name: Name of the product
company: Name of the company
country: Country of the company
industry_group: Industry group of the product
weight_kg: Weight of the product in kilograms
carbon_footprint_pcf: Carbon footprint of the product (PCF)
upstream_percent_total_pcf: Percentage of upstream emissions to total PCF
operations_percent_total_pcf: Percentage of operations emissions to total PCF
downstream_percent_total_pcf: Percentage of downstream emissions to total PCF

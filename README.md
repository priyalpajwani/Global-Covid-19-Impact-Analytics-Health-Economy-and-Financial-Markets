# Global-Covid-19-Impact-Analytics-Health-Economy-and-Financial-Markets

## Overview: 
This project analyses 15 World Bank indicators (2018–2024) across seven global regions to understand how COVID-19 affected healthcare resilience, macroeconomic performance, trade and capital markets. It uses a Python data pipeline to clean, transform and consolidate 31 raw World Bank datasets into a unified analytical dataset before developing interactive Tableau dashboards to identify regional trends, quantify cross-sector impacts, and communicate evidence based recommendations for international policymakers and development organisations, including the World Bank, IMF, WHO and the United Nations. 

## Research question: 
The analysis is centred around one overarching question: How did COVID-19 reshape healthcare demand and what ripple effects did it have on the macroeconomy?

This was explored through ten supporting research questions across three domains: 
1. Social & Health:
   1.1 To what extent did infant mortality trends slow during COVID-19, and have regional disparities narrowed during recovery?
   1.2 Did stronger pre-pandemic immunisation systems and hospital bed capacity reduce disruptions to infant mortality and life expectancy?

2. Economy:
   2.1 How did GDP evolve before, during and after COVID-19?
   2.2 How did inflation respond to the pandemic?
   2.3 How did labour markets recover across regions?
   3.4 Did tourism dependent economies experience larger declines in exports and employment?

3. Financial Markets:
   3.1 How did stock trading activity change before, during and after COVID-19?
   3.2 How did market capitalisation evolve across regions?
   3.3 Which regions experienced the strongest recovery in equity markets?
   3.4 How did market capitalisation relate to inflation across regions?

## Data: 
1. World Bank World Development Indicators (Open Data)
2. 31 raw indicator datasets transformed into a unified analytical dataset
3. 15 indicators selected for detailed analysis
4. Coverage from 2018–2024
5. Seven World Bank regions: East Asia & Pacific, Europe & Central Asia, Latin America & Caribbean, Middle East, North Africa, Afghanistan & Pakistan, North America, South Asia, and Sub Saharan Africa

The analysis combines indicators covering: hospital beds, infant mortality, life expectancy, immunisation, birth rate, GDP, inflation,  labour force, unemployment, employment in services, exports, tourism receipts, stocks traded, and market capitalisation. 

## Method: 
Built in Python (pandas) and Tableau.

The original World Bank datasets were provided as individual CSV files with countries as rows and years as columns. Each dataset was restructured using Pandas melt() into a relational format before being merged into a single analytical dataset covering healthcare, economic and financial indicators.

Exploratory Data Analysis (EDA) formed the core of the project and interactive Tableau dashboards were developed across three analytical themes: healthcare, economy and financial markets to compare regional trends before COVID-19 (2018–2019), during COVID-19 (2020–2022), and the recovery period (2023–2024). The analysis combined line charts, heatmaps, bubble charts, tables and regional dashboards to identify temporal trends, regional differences and relationships between indicators before translating these findings into policy recommendations.

## Findings: 
1. Healthcare systems, labour markets and financial markets demonstrated a clear chain reaction rather than acting independently.
2. Healthcare resilience varied substantially across regions. Countries with stronger immunisation coverage and greater hospital bed capacity generally experienced smaller disruptions to infant mortality and recovered more quickly following the pandemic.
3. Economic activity contracted sharply during 2020 before recovering across most regions, although recovery rates differed considerably. Tourism dependent economies experienced larger declines in exports and employment, while inflation peaked globally during 2022 before gradually stabilising.
4. Financial markets followed a different trajectory. East Asia & Pacific recorded the largest increase in stock trading activity during COVID-19, while North America experienced the strongest sustained growth in market capitalisation throughout the recovery period.

Overall, the analysis demonstrates that public health resilience, macroeconomic performance and financial market stability are closely interconnected rather than independent systems.

## Why this matters: 
COVID-19 exposed how disruptions in healthcare rapidly propagated into labour markets, trade and financial systems. By combining indicators across these domains rather than analysing them independently, this project provides a broader understanding of regional resilience and recovery. The findings support evidence based decision making for international organisations including the World Bank, IMF, WHO and the United Nations by identifying where healthcare investment, economic diversification and financial resilience can strengthen preparedness for future global shocks.

## Limitations: 
1. Several World Bank indicators contain missing or provisional observations for the most recent years.
2. International tourism receipts were only available up to 2020, limiting post-pandemic comparison.
3. The analysis is exploratory and identifies relationships rather than causal effects.
4. Regional aggregation provides a global perspective but may conceal substantial variation between individual countries.
5. The study relies on the quality and consistency of publicly reported World Bank data.

## Note: 
This project originated as a Data Analytics and Visualisation for Business coursework assignment at Imperial College London. My contribution included sourcing the raw World Bank datasets, defining the research questions, building the Python data preparation pipeline, transforming and integrating 31 datasets into a unified analytical dataset, designing the Tableau dashboards, conducting the exploratory data analysis, and contributing to the final report, presentation, and policy recommendations.

# COVID-19 Mortality Analysis & Visualization

## Overview
An interactive Power BI dashboard exploring what actually predicted COVID-19 mortality 
across 160 countries between 2020–2024. The analysis challenges the assumption that 
national wealth was the primary survival factor, revealing that demographic composition 
and vaccine access were far more significant.

## Key Findings
- **Wealth was a weak predictor** — GDP per capita correlated with mortality at only r=0.18. 
  The US and Belgium had higher death rates than Vietnam and Bangladesh despite being far wealthier.
- **Age structure was the strongest predictor** — r=0.56, three times stronger than wealth. 
  Countries with 20%+ of population aged 65+ faced significantly higher mortality.
- **Vaccines changed everything** — Case fatality rates in high-income countries dropped 67% 
  (from 2.41% in 2021 to 0.79% in 2024), compared to only 16% in low-income countries.
- **Healthcare infrastructure alone wasn't enough** — Hospital bed capacity showed a 
  paradoxical positive correlation (r=0.34) with mortality, explained by older populations 
  and higher testing rates in wealthier nations.

## Dashboard Pages
- Global cumulative mortality map (160 countries, August 2024)
- GDP per capita vs deaths per million — wealth correlation scatter
- Age structure vs mortality — demographic destiny scatter  
- Healthcare capacity vs deaths by income group
- Global mortality trend 2020–2024 (3 pandemic phases)
- Case fatality rate decline by income group (2021–2024)

## Dataset
- **Source:** Our World in Data COVID-19 dataset
- **Link:** https://github.com/owid/covid-19-data
- 800 observations across 160 countries at 5 annual snapshots (Dec 2020–2023, Aug 2024)
- All data transformation done in Power BI Power Query Editor

## Tools
Power BI · Power Query · DAX

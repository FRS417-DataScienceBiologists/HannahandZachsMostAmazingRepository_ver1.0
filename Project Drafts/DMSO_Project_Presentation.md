---
title: "Exploration of Metabolite Levels Across the Brains of Rats Treated with Varriable Doses of DMSO"
author: Zach Rabow and Hannah Houts
date: March 15, 2019
output: ioslides_presentation
---

# In the morning

## Getting up

- Turn off alarm
- Get out of bed

## Breakfast

- Eat eggs
- Drink coffee

# In the evening

## Dinner




Exploration of Metabolite Levels Across the Brains of Rats Treated with Varriable Doses of DMSO
========================================================
author: Zach Rabow & Hannah Houts
date: 3/15/19
output: ioslides_presentation
autosize: true

Description of the Dataset
========================================================

This is a description of the study, and how rats got injected with solvents. its a whole thing

The Original Data File
========================================================

#The data was came as an excel file that was not Tidy (r) at all. 

-data (treatment) was stored in column names, not as a vector
-this occured across 3 parts of the data:
  -the mean intensity
  -the p-value
  -the fold change

Tidying the data
========================================================

Load Data & Rename Columns 





```
Error in Untidy_DMSO_Data %>% rename(Chemical_Name = ChemicalName, Mean_Intensity_Control = mean.Control.PBS,  : 
  could not find function "%>%"
```

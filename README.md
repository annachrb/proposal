# Munich Unemployment Analysis (2000-2024)

## Description

The dataset contains yearly unemployment records across the 25 city districts of Munich, covering the years 2000 - 2024. 
Each row represents one year for one area combined with a single demographic category (gender, nationality or total) and the fitting unemployment percentage with the unemployment count and total resident count. 
The data is published under Datenlizenz Deutschland Namensnennung 2.0 and downloaded from the Munich Open Data Portal on 2026-05-15. 

## Research Questions

1. How has the unemployment percentage in Munich changed from 2000 to 2024 overall and by city area (North, East, South, West)?
2. Do unemployment percentages differ in 2024 based on gender across districts in South Munich.

We considered a third predictive RQ:
3. Can we build a simple model to predict the unemployment percentage in future years?
We cut this to keep the project focused on two questions and aligned with the course guidance to limit the proposal to at most two RQs.

## Visualisation improvement

Before:The plot had no subtitle, no data source, and used the outdated `size` argument.

After: Added a finding-based subtitle, axis labels with units, a source caption, and switched to `linewidth` for modern ggplot2.

The subtitle now states the finding directly so readers immediately understand 
what the chart shows without having to interpret it themselves.

## Group Members
- Rebecca Patrick: R.Patrick@campus.lmu.de
- Anna Chrebtov: Anna.Chrebtov@campus.lmu.de
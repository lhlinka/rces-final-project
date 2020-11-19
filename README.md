# rces-final-project

My final project repository for RCES

### Scientific Question
 
How does geochemistry and inferred volatile content evolve over the emplacement of the Columbia River Basalt Group?

### Hypothesis

The Columbia River Basalt Group consists of 350 lava flows that are divided into 5 major formations: Steens, Imnaha, Grande Ronde, Wanapum, and Saddle Moutain. The earlier emplaced Steens formation consist of more primitive magmas, therefore I predict the Steens may have a greater volatile content than the later formations.

### Dataset

[Compilation of geochemistry data from the Columbia River Plateau-Blue Mountains Province](https://drive.google.com/file/d/14ayP9bT4SRdWnwocO50IcPw0J963tqWR/view?usp=sharing)

File downloaded from the GEOROC - Geochemical database (http://georoc.mpch-mainz.gwdg.de/georoc/). 
<br/> Date of Query: November 13, 2020
<br/> Query Criteria: Query by Geologic Setting -> Continental Flood Basalts -> Yellowstone-Snake River Plain Volcanic Province -> Columbia Plateau-Blue Mountains Province -> No Further Constraint -> Sample Criteria (combined with OR) -> Type of Material: Volcanic Glass, Inclusion, Mineral, Wholerock 

### Summary of Proposed Analysis

First, I will load the .csv file of published geochemical data for the Columbia River Basalt Group; I will clean up the data file for any missing values, normalize the data to 100%, and address any inconsistent reporting of data (i.e. reporting FeO vs Fe2O3, all data will be converted to FeO*). 

Then I will use the groupby function to sort the data based on stratographic units and apply mathematical formulas to determine if there is any europium anomaly (Eu*), dysprosium anomaly (Dy), and trace element ratios to be used as proxies to infer volatile content.

Finally, to analyze the evolution of geochemistry and inferred volatile content over the emplacement of the Columbia River Basalt Group, I will make a series of plots grouped by formation including: (1) TAS diagram, (2) REE spider diagram, (3) Eu* anomaly plot, (4) Dy anomaly plot, (5) trace elements as proxies for volatile content (e.g., Nb for CO2, Ce for H2O, Dy for S), (6) a map of the geographical location of data points.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lhlinka/rces-final-project/HEAD)
# rces-final-project

My final project repository for RCES

### Scientific Question
 
How does geochemistry and inferred volatile content evolve over the emplacement of the Columbia River Basalt Group?

### Hypothesis

The Columbia River Basalt Group consists of 350 lava flows that are divided into 5 major formations: Steens, Imnaha, Grande Ronde, Wanapum, and Saddle Moutains. The earlier emplaced Steens and Imnhaha formations consist of more primitive magmas, therefore I predict the Steens and Imnaha may have a greater volatile content than the later formations.

### Dataset

[Compilation of geochemistry data from the Columbia River Plateau-Blue Mountains Province](https://drive.google.com/file/d/14ayP9bT4SRdWnwocO50IcPw0J963tqWR/view?usp=sharing)

File downloaded from the GEOROC - Geochemical database (http://georoc.mpch-mainz.gwdg.de/georoc/). 
<br/> Date of Query: November 13, 2020
<br/> Query Criteria: Query by Geologic Setting -> Continental Flood Basalts -> Yellowstone-Snake River Plain Volcanic Province -> Columbia Plateau-Blue Mountains Province -> No Further Constraint -> Sample Criteria (combined with OR) -> Type of Material: Volcanic Glass, Inclusion, Mineral, Wholerock 

### Summary of Proposed Analysis

First, I will load the .csv file of published geochemical data for the Columbia River Basalt Group; I will clean up the data file for any missing values, address anh inconsistent reporting of data, and apply mathematical formulas to normalize the major element data to 100%, calculate total alkali content, and calculate trace element ratios of interest.

Then I will use the filter, where, and groupby functions to sort the data based on stratographic formation (e.g., Steens, Imnaha, Grande Ronde, Wanapum, and Saddle Mountains) and sample type (e.g., inclusion, glass, mineral, wholerock).

Finally, to analyze the evolution of geochemistry and inferred volatile content over the emplacement of the Columbia River Basalt Group, I will make a series of plots grouped by sample type and stratigraphic formation including: (1) a boxplot of CRBG sample ages, (2) a map of the geographical location of the sample origin, (3) TAS diagram, (4) Harker diagram, (5) Zr as an index of magma differentitation, (6) histogram of measured volatile data and (7) trace elements as proxies to infer volatile content (e.g., Ce for H2O, Nb for CO2, Ba for CO2.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lhlinka/rces-final-project/HEAD)
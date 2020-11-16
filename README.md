# rces-final-project

My final project repository for RCES

### Scientific Questions
 
How do geochemistry and magma generation depths and temperatures evolve over the emplacement of the Columbia River Basalt Group?

### Dataset

[Compilation of geochemistry data from the Columbia River Plateau-Blue Mountains Province](https://drive.google.com/file/d/14ayP9bT4SRdWnwocO50IcPw0J963tqWR/view?usp=sharing)

File downloaded from the GEOROC - Geochemical database (http://georoc.mpch-mainz.gwdg.de/georoc/). 
Date of Query: November 13, 2020
Query Criteria: Query by Geologic Setting -> Continental Flood Basalts -> Yellowstone-Snake River Plain Volcanic Province -> Columbia Plateau-Blue Mountains Province -> No Further Constraint -> Sample Criteria (combined with OR) -> Type of Material: Volcanic Glass, Inclusion, Mineral, Wholerock 

### Summary of Proposed Analysis

First, I will load the .csv file of published geochemical data for the Columbia River Basalt Group; I will clean up the data file for any missing values, normalize the data to 100%, and address any inconsistent reporting of data (i.e. reporting FeO vs Fe2O3, all data will be converted to FeO*). 

Then I will group the data by formation and unit and apply mathematical formulas to determine the geochemistry in terms of magnesium number (Mg#), trace element ratios, europium anomaly (Eu*), dysprosium anomaly (Dy), and to infer the melting pressure and temperature using the Lee et al. (2009) thermobarometer which is based on magma Si and Mg contents.

Finally, to analyze the evolution of geochemistry over the emplacement of the Columbia River Basalt Group, I will make a series of plots including: (1) TAS diagram, (2) REE spider diagram, (3) Eu* anomaly plot, (4) Dy anomaly plot, (5) Pressure vs Temperature plot, (6) a map of the geographical location of data points.

### References
Lee, C. T. A., Luffi, P., Plank, T., Dalton, H. & Leeman, W. P. Constraints on the depths and temperatures of basaltic magma generation on Earth and other terrestrial planets using new thermobarometers for mafic magmas. Earth and Planetary Science Letters 279, 20–33 (2009).

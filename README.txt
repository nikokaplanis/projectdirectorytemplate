This doc describes the  working directory

Directory Architecture:

Data:
Contains all data. Within this folder are two subdirectories - Raw Data, and Processed Data. Raw Data are unmanipulated, straight from the data source. Processed Data are outputs from scripted data wrangling and transformations.

All data come from 
  

Scripts:
All R scripts are contained within the Scripts folder. The scripts have the prefix _, then a name that indicates the major function of the code. The scripts download and manipulate data, conduct analyses, and/or produce figures. 

Outputs:
Any figures and tables from preliminary analyses, but that are not final products, are saved in Outputs.

Figures:
All final figures and tables are contained in the Figures folder. All figures are produced by scripts. 
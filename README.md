README

Police and the potential effects of the urban overload hypothesis

By: Jack Lohman


Project Statement: 

The purpose of this project is to use open source police dispatch data to analyze the effects of 
The urban overload hypothesis (that decision making changes in environments with a high amount of stimuli) in a law enforcement setting.


Motivation:

This project was created for Denison Data Analytics 401 class, taught by Dr. Alexandre Scarcioffolo. Creator Jack Lohman aims to analyze the role of call volume and time to event data in the punitive outcomes of police interactions. Punitive outcomes are defined by an arrest, citation, or filed police report.  

Build Status:

The project, overseen by Dr. Scarcioffolo, is currently in the development stages, and results are not yet considered complete. 


Requirements:

Required hardware includes RStudio version 2024.12.1+563, with the following packages:
	tidyverse
	lubridate
	Survival
	survminer
	caret  
	nnet
	data.table
	kableExtra
	gridExtra
	cowplot


Data File:

As the data file is too large to be added to the repository, it is available upon request. It contains dispatched law enforcement incidents from the city of San Francisco from 2015 onwards, but only the years 2022 to 2025 are used in analysis. 

Code Files:

	Police Overload.rmd:
	The main coding file, used for data cleaning, and statistical analysis.

 
How to Use:

	Police Overload.rmd:
	*Open in RStudio, making sure that source files are in proper directory
	*Import packages in file header
	*Navigate to the "Run" menu and run all to see output
		*Ouput includes results fro,:
		*Cox PH model and associated coefficients
		*Multinomial regression and associated coefficients
	
 
Contribute:

Any contributions with the intention of genuine improvement on the base product is permitted and encouraged. 


License:
	
This data was downloaded from data.sfgov.org and has open permission for use. 

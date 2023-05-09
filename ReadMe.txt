Bonjour, Hi ! 

This is the ultimate package for making measurement on the NV with the FPGA.
It contains 
	- The Python scripts for running the experiment. 
	- Some Python scripts for analysing data that are taken with the software. 
	- Some example of high-level experiment built from the software package. 

In general, the scripts use the following library:
 - spinmob, 
   Developped by our awesome supervisor Jack Sankey. 
   This library allows to build very cosy GUIs, talk to machines easily, plot stuff very fast and more !
   I can be obtained here: https://github.com/Spinmob/spinmob
 - numpy, matplolib and compagny. 
   Those are very common libraries used by scientist. 

In this repository, the folders are:
	- software_packages:
		It contains the scripts for runnning the typical confocal experiment.
		They are Python scripts. 
		More explaination in the Readme inside this folder. 
	- examples_analysis_data:
		Various scripts for loading and analysing some common data taken with the software. 
	- examples_experiments:
		It contains examples of experiment built by assembling the experiment in "software_packages". 
	- examples_sequences:
		Example of data files for the pulse sequence builder. 
		They can be used as a base for building your personal pulse sequence. 
		You are up to add your own favorire pulse sequence ;) 
	- prev_codes:
		This folder contains scripts that are no longer used. 
		I keep them there because some piece of code might be still of interest. 

For any typo in the english language found anywhere, 
blame not me, but my proud Lac-Saint-Jean education of english,

Michael Caouette-Mansour
michael.caouette-mansour@mail.mcgill.ca
Childress Laboratory
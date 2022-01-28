
Python with Babe
Week 1

Goals
* Install Pandas, Python/Anaconda
* Generate illustrative charts - bar, line, etc

Data
* https://www.kaggle.com/johnharshith/hollywood-theatrical-market-synopsis-1995-to-2021

Plots - What Gagan is curious about
* Looking at HighestGrossers.csv, What is the average Ticket Sale per MPAA Rating? Genre?
* Looking at AnnualTicketSales.csv, Could you give me a yearly chart summary of Average Ticket Price? Total Box Office Sales?

Hints

* After you install conda, start an anaconda shell. (Anaconda Prompt in Windows Start Menu)
	# create pybabe conda environment, install pandas, jupyter, and numpy, then start a notebook
	* conda create -n pybabe python
	* conda activate pybabe
	* conda install pandas jupyter numpy
	# install matplotlib, note: you need to specify a separate channel (-c) for this install
	* conda install -c conda-forge matplotlib
	# Start a jupyter notebook
	* $ jupyter notebook
	
* Jupyter Lab is a replacement for Jupyter Notebook that provides more file features. Can you start this?

* I would start by 
	* downloading csv files
	* creating a pybabe-wk1 folder to store this work, cd into there
	* set up conda env for this project
	* launch jupyter notebook
	* import pandas in the first cell, then define av ariable with the csvfilename, then use pandas.read_csv
	* https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html
		* note: end of these man pages have an example
	* After reading csv, try to get a array out of specific columns we need
		* run min, max, average on these columns to get a sense
	* Try to create the above plots
	
Just focus on hitting the what I am curious about for this week.
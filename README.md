# class5-hw
class5 and 6 homework

Pseudocode:

A- Load data
	1- load file using argparse library
	2- check if the argument passed is a file using assert statement
	1- open file using pandas library
	2- display the data frame header (first 5 rows by default)
	3- display the total number of rows and columns

B- Organize data
	1- Access specified rows using iloc
	2- Access specified columns using iloc
	3- Access specific value using iloc

C- Compute summary statistics
	1- Compute mean for each column/feature using numpy
	2- Compute STD for each column/feature using numpy


D- Visualize the data, 1-feature (column) at a time, i.e. histogram, and save the figures to files
    1- for each column
		1.1- load feature data
		1.2- save and plot histogram (note: later while coding i went with only save and i commented out show/display in code so it doesnt have to display all one by one)

E- Visualize the data, 2-features (columns) at a time, i.e. scatter plot, and save the figures to files
	1- for each column
		1.1- for every other columns/feature (different than the value above)
			1.1.1 identify all pairs
			1.1.2 plot for all pairs
			1.1.3 save images

F- Pseudocode for adding header data to your table, for an arbitrary one of these datasets
	1-load header
	2-assign it to dataset

G- Pseudocode for an additional type of plot: Multivariate Plots, interactions between multiple variables
    1- for each column (note: after coding it turned out that for corrolation we do not need a for loop)
		1.1- load feature data
		1.2- save and plot histogram

--------------------------------------------
--------------------------------------------

Running the script:

python3 generic_parser_visualizer.py housing.data.txt

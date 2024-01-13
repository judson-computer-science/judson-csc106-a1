# Assignment 1 - Printing & Command Line Parameters
In this assignment you will print a series of gymnastics scores that are
provided at the command line.  Some basic validation will be performed before
the output is printed.

## Input
Your program will take 4 command line arguments representing 4 scores from
gymnastics events.  The program should validate that exactly 4 scores have
been provided by the user before proceeding to print them.

## Output
Your program will take the user input and print it to STDOUT (the screen)
as shown below:


	$> java Scorecard 9.2 8.5 9.0 9.9

	Gymnastics Scores
	Bars: 9.2
	Beam: 8.5
	Floor: 9.0
	Vault: 9.9


Note that the order of values provided on the command line are mapped
to each gymnastics event in the following order:

	parameter 1: Bars
	parameter 2: Beam
	parameter 3: Floor
	parameter 4: Vault

## Implementation Notes
- Remember that the name of your file should match the name of your class
- Your class should be named 'Scorecard'

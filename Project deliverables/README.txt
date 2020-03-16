The code for the project is contained in file AquariumB.js.

Dependencies:
The script requires node.js to run. Can be downloaded from: https://nodejs.org/en/download/

After this, install the dependencies IN THE WORKING FOLDER:

1. Open cmd and change directory to the working folder
2. Enter the following commands for respective installations:
	npm i logic-solver
	npm i readline-sync

The program can be run now.

NOTE: There are three modes in which it can be run.

In the second mode, while entering conditions, enter from the below as CASE-SENSITIVE and with space between each condition. You may enter from one to three conditions.

Fresh OR Saline
Dark OR Light
Cold OR Lukewarm

example inputs:
one input		-Saline
two inputs		-Cold Dark
three inputs	-Fresh Cold Light

For the limit on species, you may give any number and in cases where a list longer than it is generated, it will truncate to your prefered limit. 
 
Output will always be a list of fishes and a list denoting the three conditions required for them.


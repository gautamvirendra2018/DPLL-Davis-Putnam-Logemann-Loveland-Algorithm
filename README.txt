# DPLL - SAT solver

This project basically is an implementation of the DLPP algorithm to
solve the satisfiability problems, which naturally are the NP - Hard 
problems in the computer science.

The DPLL - algorithm means combining and propagation in search.

I have implimented the algorithm using python 3.7.6 (anaconda plateform).

# Input
Input to the program is in DIMACS format

# Output
The program prints SAT if the problem is satisfiable, otherwise UNSAT.

# Command to run the program
open python command line interface and then run 
python dpll.py

# Then, enter the DIMACS file name
# (if file is in some other folder or directory - 
  then enter path including the file name).
  
e.g. File name : sat/1.cnf

# You also can run using the jupyter notebook
# Open the finaldpll.ipynb file in the jupyter notebook. Then run the code.
# It will ask to enter the file name as above in the case of the 
command line interface.


# We have used the dataset of the edusat as the input to the code.
# I also have used some of the datsets available on the 
	"www.cs.ubc.ca/~hoos/SATLIB/Benchmarks/SAT/RND3SAT/uuf50-218.tar.gz"
	"www.cs.ubc.ca/~hoos/SATLIB/Benchmarks/SAT/AIS/ais.tar.gz"
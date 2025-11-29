### The_Leslie_Matrix_Model ###
A biological simulation that uses **Linear Algebra** and **Eigenvalue Analysis** to forecast population growth based on age groups.
This project uses the **Leslie Matrix model**, a time-based method from population ecology. It separates the population into age classes (Larvae, Juveniles, Adults) and applies a transition matrix to track survival rates and reproduction over time

Mathematical Concepts Used -
     Matrices: To represent the state of the population and transition probabilities.
	 Eigenvalues: The main/dominant eigenvalue determines long-term population growth   rate 
    
   1.	λ>1: Population grows.
   2.	λ<1: Population declines.
   3.	λ=1: Population is stable.

How to run :
    Ensure you have Python installed.
 	Install the required dependencies.
 	pip install numpy matplotlib
 	Run ‘main.py’.
 	Check the output/plots folder for the growth graph.

Project structure –
 	main.py [ All-in-one program: Leslie Matrix + simulation + graphs].
 	README.md [ Instructions and explanation].
 	output/plots [Simulation results].
     	simulation.png  {Code demo (f=[0, 0, 34], p=[0.5,0.4])}
     	increasing.png   # λ > 1 (growing population)
     	stable.png   # λ = 1 (stable population)
    	decreasing.png   # λ < 1 (shrinking population)

This MATLAB script estimates pi using Monte Carlo simulation. It randomly generates points in the unit square, counts how many fall inside the unit quarter-circle, and uses this ratio to compute an estimate of pi.
The script produces convergence plots, compares results for different sample sizes, and shows how computation time affects accuracy. It also includes a function estimate_pi(sigfigs) that estimates pi until the 
result stabilizes to the desired number of significant figures. The function displays the sampled points, shows the final estimate on the figure, prints it in the Command Window, and returns the value.
To run, simply execute the script or call result = estimate_pi(3) in MATLAB.

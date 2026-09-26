# Trapezium-rule-and-monte-carlo
An exploration of numerical integration techniques in Python — including the trapezium rule, adaptive refinement, Gaussian integral approximation, and Monte Carlo methods.

This project is part of a Numerical Analysis coursework assignment.
It explores numerical integration using the trapezium rule, gradually developing from a simple fixed-step approach into more a adaptive routine.

Experiments & Results:

Convergence tests: Increased number of trapezia and compared results until the integral value stabilized.
Range tests: Explored cutoff values for the Gaussian integral.
Accuracy control: Used trap1() to refine integrations until a specified tolerance was met.
Pendulum integral: Investigated behaviour near singularities and applied a change of variables.
Monte Carlo approach: Used random sampling to approximate Gaussian probabilities.

Plots were generated to visualize:

The behaviour and shape of each integrand
Convergence trends as the number of trapezia (n) and limits increased.
The random sampling distribution used in the Monte Carlo integration method.

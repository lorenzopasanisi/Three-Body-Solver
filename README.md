# Three-Body-Solver
Three Body Solver of Sun, Earth and Moon System (Python)


Abstract:


The goal of this final project was to use python to generate a program that would solve the famous three body problem and generate a simulation of the earth and moon orbit around the sun. The reason for the selection of this project is that it is a fascinating mathematical problem that can only be solved using computational iteration techniques such as those learnt in our Physics 77 class. The three body problem essentially consists of solving the differential equations for the positions of three particles/bodies which interact through a 1/r^2 force (in our case gravitational force)(1). The ordinary differential equations in this problem can only be solved through numerical integration and therefore computational techniques must be utilized. In this project the method for numerical integration used to approximate the positions over time of each body was the fourth order Runge-Kutta method. In order to visualize the positions over time of the three bodies, a vpython simulation was utilized. The end result was a relatively simple looking simulation which showed the orbital path of the earth and moon around the sun. Overall the program was a success and solved the differential equations to a reasonable degree of accuracy. This was made obvious by the finding that in the generated simulation the period of the earth orbiting around the sun was 373 days which is only roughly 2% different to the true value of 365 days.

Note: Program must be run on a jupyter notebook or different python program with the appropriate extensions used in the code

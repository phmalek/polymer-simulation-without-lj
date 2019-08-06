# polymer-simulation-without-lj
Polymer behaviour in a bath without particles is simulated using HOOMD. Polymer changes its shape due to Brownian motion.

'run_polymer_simulation_once.ipynb' performs exactly one simulation using HOOMD and saves computed quantities of interest. 'main_code.ipynb' calls 'run_polymer_simulation_once.ipynb' many times and finally averages every quantitiy. Plots are made.

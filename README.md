# Aula-MonteCarlo-Pythia8

# Buffon's Needle Problem (buffon.ipynb)

A needle is randomly dropped on a floor made up of evenly spaced floorboards. Determine the probability that the needle lands on a line separating floorboards.

Either through clever integration or a combination of geometry and expectation, it can be shown that this probability is directly related to pi. In the special case of the floorboards being twice as wide as the length of the needles, the probability is simply 1/pi.
Thus, a simulation of Buffon's Needle Problem can be used (although quite inefficiently) as a Monte Carlo method for approximating pi.

To adjust the parameters of the simulation, simply modify the global constants at the top of the python file.
I've only run the program up to 10,000 needles, although after a certain point the approximated value of pi doesn't converge much at all; the error falls into a cycle of growth and reduction.

# Compton Scattering (compton.ipynb)

Notebook that generate compton scattering events and produce the differential cross section histogram.

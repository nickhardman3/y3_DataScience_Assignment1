# y3_DataScience_Assignment1
The Arrhenius equation relates reaction rates with temperature according to: 𝑘 = 𝐴 exp (−𝐸𝑎/𝑅𝑇 ),
where k is the rate constant, A is the pre-exponential factor, Ea is the activation energy, R is the gas
constant (8.314 J K-1 mol-1) and T is the temperature. The so-called Arrhenius parameters, A and Ea,
have to be determined experimentally for each reaction, most commonly by using the logarithmic
form of the Arrhenius equation, ln 𝑘 = ln 𝐴 − 𝐸𝑎
𝑅𝑇. Plots of ln k vs. 1
𝑇 should be linear, with slope =
− 𝐸𝑎/𝑅 and intercept = ln A.
a) The file Ex_Arrh1.csv contains experimental data for the unimolecular thermal isomerisation of
cyclopropane to propene (CH3CH=CH2) for temperatures between 950 and 1653 K. Transform the
data to calculate ln k and 1/T and generate an Arrhenius plot for the full dataset. Use a simple linear
regression to determine the slope of your plot and use this to work out the activation energy, Ea for
these data in units of kJ per mole. Is the full dataset described well by a linear relationship?
Kinetic measurements at high temperatures were flagged as more problematic in this study (J. A.
Barnard, A. T. Cocks, R. K.-Y. Lee, J. Chem. Soc. Faraday 1, 1974, 70, 1782-1792), so prepare an
Arrhenius plot for data between 950 and 1100 K and determine the activation energy for this subset.
For both models, assess the model fit in two different ways, clearly justifying your choices, and then
compare the models to each other. Include at least one plot in your assessment.
b) The file Ex_Arrh2.csv is a pruned subset of the Arrhenius data collected for the thermal
isomerisation of cyclopropane in the NIST Kinetics Database
(https://kinetics.nist.gov/kinetics/ReactionSearch?r0=75194&r1=0&r2=0&r3=0&r4=0&p0=115071&p1=0&p2=0&p3=0&p4=0&expandResults=true&) from which data assuming 2nd order kinetics,
missing data and extreme outliers have been removed. Use statistical measures of location and
variability, along with suitable visualisation plots, to compare these results to the activation energies
you have determined in part a. Clearly justify why you have chosen the descriptive statistics used
and critically assess the models fitted in part a), comparing them to the “ideal” Arrhenius equation
suggested by the collected dataset.

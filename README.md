# C1Statistics
Note on how some of the details of the statistics of mcstas files and a re-evaluation of how many 
counts will be needed to get the C1 correction to within 0.1s.
Version 2 uses the correct Poisson statistics for the intensity randomizations and adds a line to the summary
graph that is 0.1 s below the high statistics value for C1. It is the only version worth reading.

Dec 26th Added (slightly messy) version of my analysis of Jacob's spatial variation test. Ran 
the full input file through and instrument with the CDR collimators, a 3x3 array of wavelength monitors
and a position sensitive detector at the 8m mark, using three different settings of the 4-jaw
collimator, left 2cm, middle 2cm, and right 2cm, all with full height slit. All results are done
with Poisson Monte Carlo turned on. They possiby should be re-done with the normal Monte Carlo.

Feb 8th 2023 Now have C1 analyses of left, center, and right vertical slit settings of the
4-jaw slit going to a 3x3 array of spectrum detectors and top and center 1cm sq. settings
(1cm centered in x) going to the same array.

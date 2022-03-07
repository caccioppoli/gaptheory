# gaptheory
data catalog for results of "Petrillo et. al - Testing of the  Seismic Gap Hypothesis in a realistic model for earthquake occurrence"

The file contains the OFCR model simulated earthquake catalog based on "Petrillo et al. 2020".

The file is structured as follows:
(1 col) occurrence time of the sequence
(2 col) delta*
(3 col) earthquake slipped area
(4 col) earthquake x-epicenter
(5 col) earthquake y-epicenter
(6 col) earthquake magnitude
(7 col) number of sequence

*In order to obtain the time evolution of the relaxation process (aftershocks of the sequence), starting from the first time of the sequence, t0, one can write the aftershocks occurrence time (taft) from Eq.(3) of the paper:

taft=t0+exp((1-delta)/lambda)-1,

coming from the solution of the rate and state friction law (than gives a decay of g(t) which is logarithmic in time).

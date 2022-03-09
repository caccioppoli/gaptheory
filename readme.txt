Data catalog for results of "Petrillo et. al - Testing of the Seismic Gap Hypothesis in a realistic model for earthquake occurrence" under consideration of Journal of Geophysical Research: Solid Earth.

The file contains the OFCR model simulated earthquake catalog based on "Petrillo, G., Lippiello, E., Landes, F.P. et al. The influence of the brittle-ductile transition zone on aftershock and foreshock occurrence. Nat Commun 11, 3010 (2020). https://doi.org/10.1038/s41467-020-16811-7".

The catalog is splitted in 5 consecutive subcatalogs, because of memory constraints, and is structured as follows:

(1 col) occurrence time of the sequence, (2 col) delta*, (3 col) earthquake slipped area, (4 col) earthquake x-epicenter, (5 col) earthquake y-epicenter, (6 col) earthquake magnitude, (7 col) number of sequence.

*In order to obtain the time evolution of the relaxation process (aftershocks of the sequence), starting from the first time of the sequence, t0, one can write the aftershocks occurrence time (taft) from Eq.(3) of the paper:

taft=t0+exp((1-delta)/lambda)-1.
# Music-Search-Engine
This repository combines various available and stable resources to provide a pythonic framework for music analysis and manipulation of midi files. Pymidifile is a conveniency repository aiming at bridging already existing and widely tested tools such as the data analysis library Pandas or the music21 toolkit for computer-aided musicology, adapting, combining and extending the capacities of these powerful projects to my research needs.

The Pymidifile functions can be grouped into three categories:

Conversion: midi files to and from python lists, pandas Dataframes and/or music21 scores, in all combinations.
Descriptive: extract, combine and visualize musical descriptors from any of the converted types (python lists, DataFrames or Scores).
Tranform: process parameters in any converted type, transfoming some or all of its data.
Additionally, I provide a number of command-line scripts that perform useful operations on batches of files (quantization, reformatting, feature extraction).

Main Dependencies
Pymidifile works with Python =>2.7 and >=3.6. The following libraries are needed --and are indeed essential descriptive tools-- that this repository combines:

mido for midi file management (https://github.com/olemb/mido).
Pandas for data analysis (http://pandas.pydata.org/).
music21 for symbolic music manipulations (http://web.mit.edu/music21/).
seaborn for plotting graphs and distributions (http://seaborn.pydata.org).
Other dependencies include common python scientific toolkits such as Numpy, scipy-stats and json

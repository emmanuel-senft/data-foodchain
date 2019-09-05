Data for the paper: Teaching robots social autonomy from in-situ human guidance
===============================================================================

Data and analyser files for the paper.
Contains all the requirement to regenerate each graph and perform statistical
analysis reported in the paper using the JASP software.

Structure
---------

- Main file: analyse.ipynb
- Data file 1: df.csv (game metrics and demographics)
- Data file 2: supervisor.json (data for action selection)
- JASP file for statistics: analysis.jasp (d_eat corresponds to the number of 
different eating interactions, i.e. the exposure to learning units)

How to use:
----------

Run ``jupyter notebook`` in the folder and then execute cells one by one.
To save graphs, set: ``saving = True`` and run all the cells.

For the statistical analysis, open JASP and load the analysis.jasp file. On the
left are the raw data and on the right the different test run to obtain the
values reported in the paper.

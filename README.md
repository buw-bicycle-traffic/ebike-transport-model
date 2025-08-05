# ebike-transport-model

This code is part of a publication by Leonard Arning and Heather Kaths (forthcoming). Will E-Bikes Revolutionize Urban Mobility? Development and Application of a Transport Model Differentiating Between Conventional and Electric Bicycle Traffic. European Transport Studies. DOI: TBA

01_calibrate_n.ipynb, 02_calibrate_p.ipynb, and 03_calibrate_q.ipynb

Python code which opens the PTV Visum model file, replaces the relevant part of the mode choice utility function (parameters n, p, and q, as laid out in the publication above), runs the model, outputs the relevant calibration measures, and repeats.

10_sensitivity_test.ipynb

Python code extracting model results relevant for sensitivity testing from the PTV Visum model file.

21_resimp_calibrate_n.ipynb, 22_resimp_calibrate_p.ipynb, and 23_resimp_calibrate_q.ipynb

Equivalent of files 01, 02, and 03, but for the resimplified model variant which does not differentiate between c-bike and e-bike.

31_scenario analysis.ipynb

Python code extracting model results from the PTV Visum model file for scenario analysis.

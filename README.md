# 2-CLASTA
2-CLASTA is an ImageJ plugin to analyze localization data from 2-color SMLM experiments.

This repository contains code implementing methods described in reference [1]. Please cite the corresponding paper if you use code from this repository.


## Quick guide to use 2-CLASTA plugin in ImageJ
For more detailed information, please refer to the manual "2-CLASTA_plugin_manual.pdf"

1) Make sure, a recent version of Fiji (Fiji Is Just ImageJ) is installed on your PC.
   If necessary Fiji can be downloaded from https://imagej.net/Fiji

2) Save the file "2-CLASTA_Analysis.jar" in the subfolder "plugins" of your Fiji installation.
   Alternatively, the plugin can be installed via the Fiji menu Plugins -> Install PlugIn.

3) Start 2-CLASTA in Fiji via the menu Plugins -> 2-CLASTA -> Run 2-CLASTA analysis.

4) In the subsection 'Datasources', you can select input data for each color channel to be analyzed.
   Test data for different simulated scenarios can be found in the folder "Simulations_testdata".

5) In the subsection 'Parameters', you can select your preferred analysis parameters.
   Default values are recommended.

6) Click 'Start analysis'.

7) Select desired regions of interest by dragging the gray rectangle. Click 'Next' to proceed to the
   next file. When all regions of interest have been selected, click 'Confirm'.

8) Wait for the analysis to finish. The results are displayed in a new window. Arrows on the sides 
   allow to cycle through results for individual filesets.

9) The button 'Save results' allows to save all results in an .html and .csv format in a location 
   of your choice.

10) The button 'Close' terminates the plugin window.


References
----------
<a name="ArnoldSchneider2020"></a>[1] Arnold, A.M; Schneider, M.C. et al. (2020):
  “Verifying molecular clusters by 2-color localization microscopy and significance testing.”
  In: Scientific Reports, 10.1 (2020).
  Available at: [DOI: 10.1038/s41598-020-60976-6](https://doi.org/10.1038/s41598-020-60976-6)

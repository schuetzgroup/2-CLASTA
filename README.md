# 2-CLASTA
2-CLASTA is an ImageJ plugin to analyze localization data from 2-color SMLM experiments.


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

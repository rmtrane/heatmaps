# Heatmaps

This repository contains the R-scripts for creating heat maps from a cuff links data base. The main script is the `heatmaps.R`. I suggest sourcing the script. 

The script will first ask the user some questions:

* where is the file that contains the list of genes?
* where is the folder with the output of a CuffDiff run?
* where do you want to save the heatmaps?

Next, it will present you with a list of defaults for a bunch of options. It will then ask you if you want to use the defaults. If not, it will prompt you for value for each of the options, one at a time. 

Finally, the heatmaps will be created and saved to the output folder. 
# AURORA Sample Dataset

This repository contains a subset of the AURORA dataset, a multi sensor dataset for robotic ocean exploration.
It accompanies the dataset and the report "AURORA, A multi sensor dataset for robotic ocean exploration", by Marco Bernardi, Brett Hosking, Chiara Petrioli, Brian J. Bett, Daniel Jones, Veerle Huvenne, Rachel Marlow, Maaten Furlong, Steve McPhail and Andrea Munafo.

Please refer to [https://github.com/noc-mars/ocean-data](https://github.com/noc-mars/ocean-data) for further information.

The dataset sample provided in this repository includes a subset of the data collected during cruise James Cook 125 (JC125) using the Autonomous Underwater Vehicle Autosub 6000.
It is composed of two AUV missions: M86 and M86. 

- M86 contains a sample of multi-beam echosounder data in `.all` format. It also contains CTD and navigation data in `csv` format. 

- M87 contains a sample of the camera and side-scan sonar data.  The camera data contains 8 of 45320 images of the original dataset. 
The camera data are provided in `.raw` format (pixels are ordered in Bayer format). The size of each image is of size 2448x2048. 
The side-scan sonar folder contains a one ping sample of side-scan data provided in .xtf format. 
The entire AUV navigation file is provided as part of this subset in `.csv` form.

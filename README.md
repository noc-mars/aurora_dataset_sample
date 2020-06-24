# AURORA Sample Dataset

This repository contains a subset of the AURORA dataset, a multi sensor dataset for robotic ocean exploration.
It accompanies the dataset and the report "AURORA, A multi sensor dataset for robotic ocean exploration", by Marco Bernardi, Brett Hosking, Chiara Petrioli, Brian J. Bett, Daniel Jones, Veerle Huvenne, Rachel Marlow, Maaten Furlong, Steve McPhail and Andrea Munafo.

Please refer to [https://github.com/noc-mars/ocean-data](https://github.com/noc-mars/ocean-data) for further information.

The sample dataset used in this repository contains a subset of the cruise James Cook 125 data, which is composed of two missions: M86 and M86. 

- M86 contains a sample of multi-beam echosounder data in .all format. It also contains CTD and navigation data in csv format. 
The original data is around 708 MB and it is composed of 14 files containing a specific part of the survey.

- M87 contains a sample of the camera and side-scan sonar data.  The camera data contains 8 of 45320 images of the original dataset. 
The data are provided in .raw format (pixels are ordered in Bayer format).  The size of each image is of size 2448x2048. The side-scan sonar folder contains a sample of side-scan provided in .xtf format. This original data is around 50 GB and it is composed of both raw data in .jsf format and .xtf format. 
Navigation was imported into each file .xtf file. However, this sample also contains the full sonar navigation file in csv format.

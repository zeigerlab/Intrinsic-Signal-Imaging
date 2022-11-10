# Intrinsic-Signal-Imaging
Code &amp; Apps for Running and analyzing intrinsic signal imaging experiments

* * This repository is under construction. More coming soon! * *

*For users setting up IOSI, start with the 'IOSI_RingLED_IlluminationBuild.docx' document to get your illumination set up. This can then be controlled using the MATLAB application 'NeopixelControl.mlapp'.

*To mount the Adafruit Neopixels Ring on a 4x objective, 3D print the file 'Ring LED Holder-2.stl'. This will fit a Nikon 4x Plan Apo objective - we have not tested it on objectives from other manufacturers.

*Once you have started acquiring images, use the image processing application to generate basic deltaR/R images and overlay of IOSI signals onto images of cortical vasculature. Use the MATLAB application 'iosgui.mlapp'. This app requires the additional script 'IOSGUI_ImageAnalysis.m', which does most of the image processing.

*If you need some ideas of how to synchronize whisker (or other voltage based) stimuli with imaging, check out 'ZeigerLab_IOS_WhiskerStim_ZandT.m'

*If you use resources from this repository, please cite our work! You can download the manuscript (Campos_HighSensitivityIOSI_MicroscopeAdaptations_2022.pdf) or find it on biorxiv (https://doi.org/10.1101/2022.11.08.515742)

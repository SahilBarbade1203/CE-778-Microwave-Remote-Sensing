# CE-778-Microwave-Remote-Sensing
Image Preprocessing and GIS

# Tutorial 1
This repository contains a tutorial exercise for setting up Python using the Anaconda distribution, installing necessary packages like GDAL, and working with ALOS PALSAR satellite data from the Alaska Satellite Facility. The exercise includes downloading a Level 1.1 image of a selected location, calculating the total number of pixels, identifying the path number, flight direction, absolute orbit, and polarization, and extracting the real and imaginary components of HH and HV polarizations using Python. The workflow is designed to familiarize users with handling synthetic aperture radar (SAR) data and preparing for further analysis, such as creating intensity and phase image visualizations.

# Tutorial 3
This repository contains a tutorial exercise, focusing on processing Sentinel-1 SAR images using SNAP (Sentinel Application Platform). The exercise involves downloading an SLC image of your hometown from 2024 and refining it through a series of corrections, including applying precise orbit files to update satellite position and velocity metadata, radiometric calibration to ensure accurate radar backscatter representation, and radiometric terrain flattening to eliminate biases caused by topography. It also includes geometric terrain correction using the Range Doppler Terrain Correction method to rectify distortions due to sensor tilt and topographic variations, ensuring alignment with real-world coordinates in the UTM/WGS 84 projection system. The tutorial covers essential SNAP functionalities like layer management, shapefile integration, and band arithmetic operations, guiding users through each processing step with instructions to generate a refined and geocoded SAR image.

# Tutorial 4
This repository provides a tutorial, focusing on analyzing ALOS PALSAR L1.1 data, downloaded from the ASF Data Search portal. The assignment involves two tasks: first, plotting the intensity for both polarizations on normal and logarithmic scales, along with generating a stacked RGB image. Second, selecting two distinct features from the ALOS data (e.g., water bodies, forests, urban areas, etc.), cropping the regions, and plotting histograms of intensity and sigma naught for both features to compare and derive meaningful conclusions. The tutorial emphasizes key aspects of SAR data analysis, including intensity visualization, feature extraction, and statistical comparisons.





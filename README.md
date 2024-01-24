
# LAND USE / LAND COVER CLASSIFICATION USING DEEP LEARNING BASED OPTIMAL FEATURE EXTRACTION AND EVOLUTIONARY FEATURE SELECTION TECHNIQUES

The system proposes a new method of performing Land Use / Land Cover classification in the remotely sensed images. 


## Input LISS IV Madurai Image

![App Screenshot](https://github.com/GladimaNisia/Ph.D-Project/assets/156109220/d982e490-a386-4be1-84a5-fa1e1aa167ab)

## Output Classified LISS IV Madurai Image

![App Screenshot](https://github.com/GladimaNisia/Ph.D-Project/assets/156109220/92c1dc3e-e3ca-46c5-8afd-2a9c941eb9e6)
## Modules

1. Feature Extraction using Ensemble of Object Based Textural Features and Deep Features
2. Feature Extraction using Two-Stage Textural Feature Method with Convolutional Neural Network
3. Optimal Feature Selection using Evolutionary Techniques. 
       

## Module Explanation

### Module 1: Feature Extraction using Ensemble of Object Based Textural Features and Deep Features
This module deals with the feature extraction method, using the Object-Based CNN. The features extracted using the object-based strategy along with deep features from CNN produces efficient features for classification process. 

### Module 2: Feature Extraction using Two-Stage Textural Feature Method with Convolutional Neural Network
This module deals with the feature extraction method, using a Two-stage textural feature method. The obtained feature set is an ensemble of features with Gabor feature, RLBP feature and deep features.

### Module 3: Optimal Feature Selection using Evolutionary Techniques
This module deals with the feature selection techniques that can bring out the most relevant optimal features by an ensemble of feature aggregation and feature selection methods from the extracted feature set. Two feature selection methods are proposed. They are Enhanced Selective Deep Feature Basket-based Firefly (ESDFBF) Algorithm method and Wrapper-based Random Search strategy with Mutual Information (WRSMI) method.  
## Software Used

- MATLAB 2020a
- ArcMap (Version: 10.4.1)

## Dataset Used

### LISS IV Madurai Image
- The dataset chosen for implementation is Madurai Image from Indian Remote Sensing Satellite P6 Version (IRS P6). The IRS P6 is also known as ResourceSat-1. The Linear Imaging Self-Scanning Sensor (LISS) IV is the high resolution multi-spectral sensor which operates in spectral bands namely B2, B3 and B4. The spatial resolution is 5.8 meters. 

### Sentinel 2A Kanyakumari Image
- The  dataset chosen for implementation is Kanyakumari Image from Sentinel 2A Satellite. The Sentinel 2 remote sensing images are part of Copernicus Sentinel-2 mission. The satellite carries Multispectral Imager (MSI). The sensor of this satellite can deliver 13 spectral bands within the range of 10 to 60m pixel size. Each band is about 10, 20, or 60 meters in pixel size. For this project, the Color Infrared band combination is done by combining band B8, B4 and B3. 
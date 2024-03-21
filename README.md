# In-situ-surface-porosity-prediction-in-DED printed SS316L parts using multimodal sensor fusion
This GitHub repository maintains data associated with the models used in "In-situ surface porosity prediction in DED (directed energy deposition) printed SS316L parts using multimodal sensor fusion".

The repository contains 5 documents.

**1. Surfels.xlsx**  -  Contains the ground truth data (area percentage of porosity, as obtained from ImageJ software) for all surface elements ("surfels"). 
Surfels with percentage area of pores < 1% are classified as non-porous and those with area percentages > 2% are classified as porous. 

**2. Tensor_data_72_surfels.zip**  -  Contains the spectrogram data from Accelerometer and Acoustic Emission signals pertaining to printing and milling tracks for all 72 surface elements in a zip file. 

**3. Script to convert Matlab Tensor data to Numpy.ipynb**   -  The spectrogram tensor data in .mat file to be converted into numpy format that can be used for CNN models and predictions.

**4. CNN Model Architecture and Predictions.ipynb**  -  The CNN architectures for the various models developed including k-fold validation.

**5. LIME_Explanations_Porosity_Predictions.ipynb** - Python script to explain the CNN model predictions using LIME

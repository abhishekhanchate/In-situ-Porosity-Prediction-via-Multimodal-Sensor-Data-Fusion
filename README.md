# In-situ-Porosity-Prediction-via-Multimodal-Sensor-Data-Fusion
In-situ Surface Porosity Prediction in Directed Energy Deposition (DED)-printed SS316L Parts via Multimodal Sensor Data Fusion

This GitHub repository maintains data and code base associated with the models used in "In-situ Surface Porosity Prediction in Directed Energy Deposition (DED)-printed SS316L Parts via Multimodal Sensor Data Fusion".

The repository contains -
- Surfels.xlsx - Contains the ground truth data (area percentage of porosity, as obtained from ImageJ software) for all surface elements ("surfels"). Surfels with percentage area of pores < 1% are classified as non-porous and those with area percentages > 2% are classified as porous.
- Tensor_data_72_surfels.zip - Contains the spectrogram data from Accelerometer and Acoustic Emission signals pertaining to printing and milling tracks for all 72 surface elements in a zip file.
- Script to convert Matlab Tensor data to Numpy.ipynb - The spectrogram tensor data in .mat file to be converted into numpy format that can be used for CNN models and predictions.
- CNN Model Architecture and Predictions.ipynb - The CNN architectures for the various models developed including k-fold validation.
- LIME_Explanations_Porosity_Predictions.ipynb - Python script to explain the CNN model predictions using Local Interpretable Model-Agnostic Explanations (LIME)

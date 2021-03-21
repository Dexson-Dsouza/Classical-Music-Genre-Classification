# Classical-Music-Genre-Classification
This project focuses on classifying Classical Music into its sub-genres. Algorithms like K-Nearest Neighbor, Random Forest, Support Vector Machine, Multi-Layer Perceptron and Recurrent Neural Network were used to classify music into four sub-genres like Baroque, Renaissance, Orchestral and Opera.

### Prerequisite
1. Python
2. pip
3. Jupyter Notebook
4. Numpy
5. Pandas
6. Scipy
7. Matplotlib
8. Sklearn
9. Librosa

### Dataset Used
Custom dataset was created for this project. This dataset consisted of 105 audio files of each genre and each file had a duration of 15-20 secs. During Feature Extraction, various features like Zero Crossing rate (ZCR), Mel-Frequency Cepstral Coefficient (MFCC), Spectral Bandwidth, Spectral Rolloff, Spectral Contrast, Spectral Centroid, etc. were extracted from the dataset. The end result is stored in the dataset.csv file. Total 36 features were extracted.
The repo does not consist of audio files as they were too large in size but you can find the code for feature extraction.


| Algorithm  | KNN | Random Forest | Support Vector Machine | Multilayer Perceptron |
| ---------- | --- | ------------- | ---------------------- | --------------------- |
| Accuracy  | 86.5%  |85.4%  |84.4%  |79.2%  |


### Additional information
This project is a research based on the ability of Machine Learning Algorithms to classify the music into its various genres.
* main.ipynb - This file consists of code for all the required steps i.e. Feature Extraction, Data Normalization, Training the model and Testing the model with 4 different algorithms.
* dataset.csv - It is the dataset used. Dataset was split into 80% training and 20% testing.
* config1.py - This file contains the configuration required to create the dataset.

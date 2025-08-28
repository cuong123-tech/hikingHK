# Hiking Trails Classification in Hong Kong
## Overview
This project classifies hiking trails in Hong Kong using textual and numerical features. Text data is processed with various techniques, and clustering is performed using K-Means and DBSCAN algorithms to group trails into meaningful categories.
## Dataset

Source: Data on hiking trails in Hong Kong, including textual features (e.g., trail name, description) and numerical features (e.g., length, elevation, difficulty rating).
Format: CSV file with columns for text and numerical data.

## Features

### Text Processing:

Label Encoding: Converts categorical text (e.g., difficulty levels) to numerical values.
One-Hot Encoding: Represents categorical variables as binary vectors.
Bag of Words (BoW): Creates a sparse matrix of word frequencies.
TF-IDF: Transforms text into term frequency-inverse document frequency vectors.


### Numerical Features: Trail length (km), elevation gain (m), and difficulty scores....

### Clustering Algorithms

K-Means: Groups trails into K clusters based on combined text and numerical features.
DBSCAN: Clusters trails by density, identifying outliers (e.g., unique trails).


### Clone the repository:
bashgit clone [https://github.com/yourusername/hiking-trails-classification.git](https://github.com/cuong123-tech/hikingHK.git)

### Install dependencies

### Requires 

Python 3.8+ and libraries like scikit-learn, pandas, numpy, and matplotlib

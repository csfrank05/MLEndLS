# Mile End London Sounds (MLEndLS)
### Machine learning (ML) implementation in python for auditory scene analysis

Caitlin Frank
Student ID: 221086973

## Problem formulation
In the project, we aim to solve two machine learning problems.
1. Build a ML pipeline to predict whether an audio segment has been recorded indoors or outdoors. Binary classification
2. Self-formulated ML problem

## Machine Learning pipeline
- Data preprocessing
- Transformation
  - Feature extraction
  - Feature selection
- Methodology
  - Training (convolutional NNs in time?)
  - Validation (incl. performance assessment)
  
### Basic problem
- Clean outliers
- Preprocessing: Audio Scene Analysis (ASA)
  - divide sample into frames
  - multiply frames by window function
- Transformation: feature extraction by Acoustic Background Spectrum (ABS)
  - power spectrogram
  - transient noise rejection (requires validation, 5th percentile loudness should work
  - take logs
  - (optional) normalise
- Methodology
  - kNN binary classification
  - CNN?

## Dataset
- Describe the dataset, preprocessing, exploratory visualisations
- Data cube representation? Hierarchical indexing?
- Read about audio signal feature extraction (pitch and amplitude for sure)

## Results
- carry out pipeline and explain results
- ambitious but clear presentation of results? Synesthesia-informed data presentation?

## Conclusions

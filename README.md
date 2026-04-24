# Homework Portfolio
University of Oklahoma | Fall 2025

A collection of neuroscience data analysis assignments covering EEG signal processing, 
machine learning-based neural decoding, and fMRI brain imaging analysis.

---

## HW2 — EEG Spectral Analysis
**File:** `HW2_EEG_Spectral_Analysis.ipynb`  
**Dataset:** [EEG During Mental Arithmetic Tasks (PhysioNet)](https://physionet.org/content/eegmat/1.0.0/)

- Power Spectral Density (PSD) comparison across background vs. task conditions
- Spectrogram analysis for time-frequency representation
- Alpha band (8–12 Hz) time-domain signal visualization
- Topomap of average PSD in alpha band across conditions

**Stack:** MNE-Python · NumPy · Matplotlib

---

## HW3 — EEG Classification
**File:** `HW3_EEG_Classification.ipynb`  
**Dataset:** [EEG During Mental Arithmetic Tasks (PhysioNet)](https://physionet.org/content/eegmat/1.0.0/)

- Binary classification (background vs. task) using raw EEG signals
- Evaluation metrics: Accuracy, Balanced Accuracy, F1 Score
- 5-Fold Cross Validation
- Feature engineering: extraction, transformation, and selection
- Comparison of Logistic Regression vs. alternative ML classifier

**Stack:** MNE-Python · scikit-learn · NumPy · Matplotlib

---

## HW4 — fMRI GLM Analysis
**File:** `HW4_fMRI_GLM_Analysis.ipynb`  
**Dataset:** [Simultaneous EEG-fMRI (Mendeley)](https://data.mendeley.com/datasets/crhybxpdy6/2)

- fMRI parameter extraction from NIfTI header (voxel size, TE, TR)
- GLM analysis without HRF convolution on single voxel signal
- GLM analysis with HRF convolution on single voxel signal
- T-contrast brain map visualization for eyes open / eyes closed conditions

**Stack:** Nilearn · FSL · NumPy · Matplotlib

---

## HW5 — fMRI Brain Connectivity Analysis
**File:** `HW5_fMRI_Connectivity.ipynb`  
**Dataset:** [Simultaneous EEG-fMRI (Mendeley)](https://data.mendeley.com/datasets/crhybxpdy6/2)

- ROI time series extraction using MNI152 template (MSDL atlas)
- Functional connectivity via correlation matrices (EO vs. EC)
- Connectome visualization on brain glass schematics
- Graph theoretic measures: local (Clustering Coefficient, Local Efficiency, Degree) and global (Global Efficiency, Modularity, Characteristic Path Length)
- Sparse inverse covariance (Graphical Lasso) based connectivity analysis

**Stack:** Nilearn · NetworkX · scikit-learn · Matplotlib

---

## Environment
- Python 3.x
- MNE-Python
- Nilearn
- scikit-learn
- NetworkX
- NumPy · SciPy · Matplotlib

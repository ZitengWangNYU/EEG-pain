## Overview
This repository contains code and resources for a computational neuroscience research project focused on optimizing machine learning models for identifying chronic pain patients using resting-state electroencephalographic (EEG) signals. The primary objective was to improve upon previous methodologies that achieved a 57% accuracy, slightly surpassing chance levels, as reported in the study "Brain dysfunction in chronic pain patients assessed by resting-state electroencephalography", which can be found in https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7195856/.

## Key Contributions
- Expansion of Feature Space: The research extended beyond the use of power spectral density (PSD) features in electrode space by computing average relative power features across diverse brain regions in source space.
- Significant Findings: Statistically significant differences in features within the insular cortex and postcentral sulcus were discovered between patient and control groups, enhancing the understanding of chronic pain markers in EEG signals.
- Enhanced Models: The project explored multiple machine learning models, including SVM, Adaboost, and Gradient Boost, resulting in a 7% improvement over baseline models.
## Contents
- Code: Python scripts and Jupyter notebooks used for data preprocessing, feature extraction, model training, and evaluation.
- Data: The dataset can be found here: https://osf.io/srpbg/
- Results: Detailed results, including performance metrics, visualizations, and analysis outputs can be found in the jupyter notebooks
## Experiments
### EEG Analysis Baseline:
The baseline model includes five sets of features: the relative powers for all channels, all regions, statistically significant channels, all source labels, and statistically significant source labels.
### EEG Analysis 1: 
With 1/f noise reduction
### EEG Analysis 2:
With 1/f noise as features

## Getting Started
To replicate or build upon this research, follow these steps:
1. Download the public dataset
2. Preprocess the dataset
3. Follow the steps in the jupyter notebooks, which include feature extraction, model training, and evaluation.

## References
Ta Dinh S, Nickel MM, Tiemann L, May ES, Heitmann H, Hohn VD, Edenharter G, Utpadel-Fischler D, Tölle TR, Sauseng P, Gross J, Ploner M. Brain dysfunction in chronic pain patients assessed by resting-state electroencephalography. Pain. 2019 Dec;160(12):2751-2765. doi: 10.1097/j.pain.0000000000001666. Erratum in: Pain. 2020 Jul 1;161(7):1684. PMID: 31356455; PMCID: PMC7195856.

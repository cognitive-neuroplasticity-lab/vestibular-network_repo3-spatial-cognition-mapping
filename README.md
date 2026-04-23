# Spatial Cognition Mapping in Vestibular Brain Networks

A neuroimaging analysis project examining how vestibular-related brain networks support spatial cognition, navigation, and multisensory orientation.

This repository extends prior vestibular network analyses into cognition-focused modelling by linking network signatures with spatial task performance, participant strategy profiles, and reproducibility metrics.

## Project Aim

To test whether connectivity patterns within vestibular-associated neural systems meaningfully relate to spatial cognition performance, and to establish a scalable framework for future predictive and translational analyses.

## Dataset Used

- Domain: Vestibular and Spatial Neuroplasticity  
- Focus: Brain networks supporting orientation and navigation  
- Population: Healthy adult proof-of-concept samples  
- Design: Cross-sectional cognitive neuroimaging modelling  
- Modalities Referenced: fMRI, EEG-fMRI, MEG, behavioral task data

## Analytical Scope

This repository focuses on a proof-of-concept framework using:

- Publicly relevant vestibular and spatial paradigms
- Network-level regional signatures
- Connectivity-performance association modelling
- Navigation strategy clustering
- Reproducibility and feature stability testing

## Why a Mapping Pipeline Was Used

Vestibular neuroscience often emphasizes sensory processing, while spatial cognition research often emphasizes behavior. A mapping pipeline was used to bridge these domains and test how vestibular-network organization may support higher-order navigation performance.

This preserves the central scientific question: how balance and self-motion systems interact with cognition.

Future repositories may extend this framework using subject-level neuroimaging datasets and predictive models.

## Methods

The repository used a lightweight and scalable workflow:

- Survey spatial cognition paradigms and usable datasets
- Profile vestibular-region connectivity signatures
- Quantify associations with spatial performance
- Cluster participants into navigation strategy groups
- Evaluate robustness using bootstrap and ranking analyses

## Main Findings

- Core vestibular-spatial regions showed differentiated connectivity profiles
- Stronger connectivity was associated with better spatial task performance
- Participants could be grouped into distinct navigation strategy profiles
- Hippocampal and vestibular cortical regions ranked highly in association strength
- Findings remained stable under bootstrap reproducibility checks

## Repository Workflow

### Notebook 1 - Spatial Dataset Landscape

Mapped available paradigms and identified resources suitable for connectivity-based spatial analyses.

### Notebook 2 - Vestibular Network Signature

Profiled engagement of vestibular and spatial brain regions across task contexts.

### Notebook 3 - Spatial Performance Association

Tested relationships between network connectivity and behavioral accuracy.

### Notebook 4 - Navigation Strategy Clustering

Clustered participants into distinct behavioral-neural navigation profiles.

### Notebook 5 - Spatial Mapping Reproducibility

Evaluated robustness of findings using resampling and feature stability analyses.

## Limitations

- Proof-of-concept simulated modelling rather than raw cohort ingestion
- Region-level summaries rather than voxelwise inference
- Cross-sectional framework rather than longitudinal adaptation modelling
- Simplified behavioral features for scalable demonstration

## Future Directions

- Real vestibular fMRI dataset implementation
- Clinical dizziness and balance cohorts
- VR navigation experiments
- Longitudinal vestibular rehabilitation tracking
- Predictive modelling of spatial performance outcomes

## Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Maintained By

Aditya Sundaray

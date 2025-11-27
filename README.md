# LuccaProject_FC

TITLE: Brain networks that best predict individual working memory performance. A project based on EEG functional connectivity and TAP scores

PROJECT DESCRIPTION: We are developing a predictive model for individual working memory (WM) performance based on brain network activity derived from resting-state EEG data. Specifically, we are calculating functional connectivity (FC) matrices from source-localized EEG data and then using these matrices to train a machine learning model (such as Lasso Regression or Support Vector Machines) to map from connectivity to behaviour. The project is for anyone interested in the neural correlates of cognition and investigating the connectivity for cognitive traits. The goal is to identify specific brain networks (groups of interconnected nodes) that are most predictive of working memory scores or any other cognitive domain that collaborators may be interested in investigating! The data will be taken from an open source data set: Max Planck Institut Leipzig Mind-Brain-Body Dataset - LEMON.

GOALS FOR BRAIN HACK:
**GOAL 1: Feature Extraction**  
  A) Derive the dynamic functional connectivity (dFC) matrix. 
    Decisions to be made are: 
      i) method of source reconstruction (e.g. forward and inverse model)
      ii) type of connectivity (e.g. coherence, phase lock value, etc.)
      iii) Time window.
  C) Select different networks (groups of nodes, e.g. those that comprise the fronto-parietal network) and frequencies (e.g., theta) based on previous literature.
  C) Run a PCA analysis
  D) Transform the matrices into a readable format for the specific machine learning model. 

**GOAL 2: Train Model**
TWO OPTIONS:
1) Train a LASSO regression to predict subjects' cognitive battery scores (e.g. working memory) based on functional connectivity.
2) (If we categorize scores) Train an SVM model and compare the accuracy rates of different SVM models used to predict scores in different cognitive domains. 


**GOAL 3 (optional): Obtain dFC from individual MRI and run the models with this more accurate feature**
This option requires segmentation of each subject's MRI into an atlas e.g. (Desikan–Killiany). 

COMMUNICATION CHANNEL:
Google workspace

WHAT WILL PARTICIPANTS LEARN:
- foundational concepts on functional connectivity
- what a predictive model machine learning is and how to create one
- using Brainstorm

DATA TO USE: open source data from LEMON repository Max Planck CBS. We will use behavioral data (results of TAP Working Memory test) and EEG data

SKILLS:
- knowledge of neuropsychological testing for cognitive domains and excel -> useful for feature extraction of the behavioral data LEMON provides
- knowledge of interpreting dynamic functional connectivity from EEG. 
- general knowledge of supervised and unsupervised machine learning models. 
- good understanding of general linear regressions (GLMs)
- brainstorm software basics. (A MATLAB-based application).
- basic Python skills for machine learning.

IMAGE (look Canva)

PROJECT LABELS:
- type: coding methods
- development status: basic structure
- EEG, machine learning, neural networks, PCA, statistical modeling
- tools: Brainstorm
- programming language: Python, MATLAB
- modalities: behavioral, EEG
- git skills: ???



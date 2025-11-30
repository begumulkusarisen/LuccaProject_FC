

PROJECT DESCRIPTION:We are developing a predictive model for individual working memory (WM) performance based on brain network activity derived from resting-state EEG data. Specifically, we are calculating functional connectivity (FC) matrices from source-localized EEG data and then using these matrices to train a machine learning model (such as Lasso Regression) to map from connectivity to behaviour. The project is for anyone interested in the neural correlates of cognition and investigating the connectivity for cognitive traits. The goal is to identify specific brain networks (groups of interconnected nodes) that are most predictive of working memory scores or any other cognitive domain that collaborators may be interested in investigating! However, the most involved network in the domain of working memory is the fronto-parietal, along with several ROIs such as DLPC, ACC, and anterior insula. Hence, we would form hypotheses based on the literature showing these networks and areas in relation to the task
The data will be taken from an open-source data set: Max Planck Institut Leipzig Mind-Brain-Body Dataset - LEMON.

GOALS FOR BRAIN HACK:
GOAL 1: Feature Extraction
A) Derive the dynamic functional connectivity (dFC) matrix. B) Select different networks (groups of nodes, e.g. those that comprise the fronto-parietal network) and frequencies (e.g., theta) based on previous literature. C) Compute jump length and other indices of interest D) Transform the matrices into a readable format for the specific machine learning model.

GOAL 2: Train Models
Train a LASSO regression to predict subjects' cognitive battery scores (e.g. working memory) based on functional connectivity.
(Optional): unsupervised clustering of dFC matrices.

GOAL 3 (optional): Obtain dFC from individual MRI and run the models with this more accurate feature This option requires segmentation of each subject's MRI into an atlas e.g. (Desikan–Killiany).



SKILLS:
- knowledge of neuropsychological testing for cognitive domains and excel -> useful for feature extraction of the behavioral data LEMON provides
- knowledge of interpreting dynamic functional connectivity from EEG. 
- general knowledge of supervised and unsupervised machine learning models. 
- good understanding of general linear regressions (GLMs)
- brainstorm software basics. (A MATLAB-based application).
- basic Python skills for machine learning.



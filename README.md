# LuccaProject_FC

**Step 1: Feature Extraction**  
  A) Derive the dynamic functional connectivity (dFC) matrix. 
    Decisions to be made are: 
      i) method of source reconstruction (e.g. forward and inverse model)
      ii) type of connectivity (e.g. coherence, phase lock value, etc.)
      iii) Time window.
  B) Select different networks (groups of nodes, e.g. those that comprise the fronto-parietal network) and frequencies (e.g., theta) based on previous literature.
  C) Run a PCA analysis
  D) Transform the matrices into a readable format for the specific machine learning model. 

**Step 2: Train Model**
TWO OPTIONS:
1) Train a LASSO regression to predict subjects' cognitive battery scores (e.g. working memory) based on functional connectivity.
2) (If we categorize scores) Train an SVM model and compare the accuracy rates of different SVM models used to predict scores in different cognitive domains. 


**Step 3 (optional): Obtain dFC from individual MRI and run the models with this more accurate feature**
This option requires segmentation of each subject's MRI into an atlas e.g. (Desikan–Killiany). 

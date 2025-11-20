# LuccaProject_FC

**Step 1: Feature Extraction**  
  A) Derive the dynamic functional connectivity (dFC) matrix. 
    Decisions to be made are: 
      i) method of source reconstruction (e.g. forward and inverse model)
      ii) type of connectivity (e.g. coherence, phase lock value, etc.)
      iii) Time window.
  B) Select different networks (groups of nodes, e.g. those that comprise the fronto-parietal network) and frequencies (e.g., theta) based on previous literature.
  C) Transform the matrices into a readable format for the specific machine learning model. 

**Step 2: Train Model**
Train different SVM models to predict subjects' working memory scores based on functional connectivity.
Compare the accuracy rates of SVM models based on the network used to predict the scores. 


**Step 3 (optional): Obtain dFC from individual MRI and run the models with this more accurate feature**
This option requires segmentation of each subject's MRI into an atlas e.g. (Desikan–Killiany). 

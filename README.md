# Data_iOP
Data set for Koh et al. "Plasma multi-omic and cardiac imaging network signatures predict poor long-term outcomes after acute myocardial infarction"

## XXX_dataset_XXXX.txt 
- Contains the raw data files for lipidomics and proteomics dataset for both CDCS (tagged with _CDCS.txt) and IMMACULATE cohort (tagged with _IMMACULATE.txt) used for integrative analysis in the manuscript above. 
- The expression values have been log(base 2)-transformed and outlying samples have been removed. 

## PredictedClassprobabilities_XXXX.txt 
- Contains the results of using the estimated network signatures to predict the class probability that each subject belong to.
- Each file contains the predicted class as well as the actual class information and the files are tagged separatedly for the two main comparisons in the manuscript: (A) event-free (EF) patients versus patients with major adverse cardiac outcomes (MACE) and (B) event-free (EF) patients versus patients with heart-failure (HF) as the clinical end-point.
-
## SomalogicProtein_MetaInfo.txt 
- Contains protein information that can be matched to the somalogic ID in the protein dataset

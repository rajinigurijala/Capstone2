# Capstone2

Source
This Data Set is downloaded from UCI Machine Learning Repository

Download Link: https://archive.ics.uci.edu/ml/machine-learning-databases/00277/

Original File Name: ThoraricSurgery.arff

Converted to CSV: https://pulipulichen.github.io/HTML5-BayesNet-Tools/arff2csv/

Converted File: ThoraricSurgery.csv

Files

The Jupyter notebook Thoracic Surgery Analysis contains the main code.

Abstract

The data is dedicated to the classification problem related to the post-operative life expectancy in the lung cancer patients: class 1 - death within one year after surgery, class 2 - survival.

Data Set Information

The data was collected retrospectively at Wroclaw Thoracic Surgery Centre for patients who underwent major lung resections for primary lung cancer in the years 2007-2011. The Centre is associated with the Department of Thoracic Surgery of the Medical University of Wroclaw and Lower-Silesian Centre for Pulmonary Diseases, Poland, while the research database constitutes a part of the National Lung Cancer Registry, administered by the Institute of Tuberculosis and Pulmonary Diseases in Warsaw, Poland.

The data folder contains the converted data file in CSV format. The Jupyter notebook file shows how the original data set was cleaned to be used for this project.

 Attribute Information:
 
 Attribute	Description
 DGN	Diagnosis	 Diagnosis - specific combination of ICD-10 codes for primary and secondary as well multiple tumors if any (DGN3,DGN2,DGN4,DGN6,DGN5,DGN8,DGN1)
 PRE4	FVC	 Forced vital capacity - FVC (numeric)
 PRE5	FEV1	 Volume that has been exhaled at the end of the first second of forced expiration - FEV1 (numeric)
 PRE6	Performance	 Performance status - Zubrod scale (PRZ2,PRZ1,PRZ0)
 PRE7	Pain	 Pain before surgery (T,F)
 PRE8	Hemoptysis	 Hemoptysis before surgery (T,F)
 PRE9	Dyspnea	 Dyspnea before surgery (T,F)
 PRE10	Cough	 Cough before surgery (T,F)
 PRE11	Weakness	 Weakness before surgery (T,F)
 PRE14	Tumor Size	 T in clinical TNM - size of the original tumor, from OC11 (smallest) to OC14 (largest) (OC11,OC14,OC12,OC13)
 PRE17	Diabetes Mellitus	 Type 2 DM - diabetes mellitus (T,F)
 PRE19	MI_6mo	 MI up to 6 months (T,F)
 PRE25	PAD	 PAD - peripheral arterial diseases (T,F)
 PRE30	Smoking	 Smoking (T,F)
 PRE32	Asthma	 Asthma (T,F)
 AGE	Age	 Age at surgery (numeric)
 Risk1Y	Death_1yr	 1 year survival period - (T)rue value if died (T,F)

References:

https://www.cdc.gov/cancer/

https://onlinelibrary.wiley.com/doi/full/10.3322/caac.21551

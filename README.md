# LUAD-Feature-Selection-Project
This project works on identifying biomarkers for Lung Adenocarcinoma (LUAD) patients, while building a classifier that can differentiate between LUAD patients from Normal patients. We propose a framework that applies an ensemble of feature selection techniques to identify genes highly correlated to LUAD. Utilizing LUAD RNA-seq data from the Cancer Genome Atlas (TCGA), we employed mutual information (MI) and recursive feature elimination (RFE) feature selection techniques along with support vector machine (SVM) classification model.


The proposed framework has identified twelve potential biomarkers that are found to be highly correlated with LC in many LC types especially LUAD. A predictive model has been trained utilizing the identified biomarker expression profiling and performance of 97.73 % was achieved. In addition, upon performing differential gene expression analysis, we could find that all 12 genes were significantly differentially expressed between normal and LUAD tissues and strongly correlated with LUAD according to previous reports.

The final model (12 genes) was tested on an external dataset from GEO GSEGSE81089 (attached in the files), and produced 96.30 %. 

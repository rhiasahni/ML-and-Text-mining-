

This compendium contains the code, data, and analysis for the assessment to predict breast cancer patient outcomes using clinical and multi-omic data. The assessment utilizes the dataset provided by The Cancer Genome Atlas Program.

Contents:
README.md: This file providing an introduction to the compendium.
code: Directory containing the code for the pipeline used to process and analyze the data.
data source: Directory containing the dataset files, including clinical information and omics data.
computational environment: Record of the computational environment used for the analysis.
report.pdf: A report summarizing the study in an academic paper format.

Abstract:
The aim of this study is to assess the predictive capacity of clinical data and multi-omic data derived from breast tumors to predict patient outcomes. Eight different models were trained using a machine learning algorithm, considering various sets of features including clinical features, individual omic data types, and combinations of multiple omics. The models were evaluated using the Area Under the ROC Curve (AUC) as a performance metric. The results showed varying predictive performances depending on the set of features used. While some models exhibited poor discriminatory power or overfitting, others showed limited improvement in predictive performance. Overall, Random Forest, chosen for its ability to handle high-dimensional data, demonstrated limitations in predicting breast cancer outcomes. Further refinement of feature selection and exploration of alternative modeling techniques are recommended.

For a more detailed description of the study, methods, results, and discussion, please refer to the full report.

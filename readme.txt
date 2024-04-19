# CPMI
Code and datasets for paper " CPMI: Comprehensive neighborhood-based perturbed mutual information for identifying critical states of complex biological processes"

## CPMI: Comprehensive neighborhood-based perturbed mutual information for identifying critical states of complex biological processes
There exists a critical transition or tipping point during the complex biological process. Such critical transition is usually accompanied by the catastrophic consequences. Therefore, hunting for the tipping point or critical state is of significant importance to prevent or delay the occurrence of catastrophic consequences. However, predicting critical state based on the high-dimensional small sample data is a difficult problem, especially for single-cell expression data. In this study, we proposed the comprehensive neighbourhood-based perturbed mutual information (CPMI) method to detect the critical states of complex biological processes. The CPMI method takes into account the relationship between genes and neighbours, so as to reduce the noise and enhance the robustness.This method is applied to a simulated dataset and six real datasets, including an influenza dataset, two single-cell expression datasets and three bulk tumor datasets. The method can not only successfully detect the tipping points, but also identify their dynamic network biomarkers (DNBs). In addition, the discovery of transcription factors (TFs) which can regulate DNB genes and nondifferential ¡®dark genes¡¯ validates the effectiveness of our method. The numerical simulation verifies that the CPMI method is robust under different noise strengths and is superior to the existing methods on identifying the critical states.

## Data avalability
The datasets supporting the conclusions of this article can be downloaded from the NCBI (http://www.ncbi.nlm.nih.gov/geo/) and TCGA (http://cancergenome.nih.gov) repositories. To ensure reproducible results, the original code is available at https://github.com/R-J-06/CPMI.

## readme
MATLAB environment.

Sample dataset:

Information about the sample dataset(Influenza:GSE30550)
"input data control_flu.txt, subject1_case.txt" £¨The first individual in the GSE30550 dataset.£©
running pipeline: CPMI_subject1.m

Information about the sample dataset(KIRP)
"input data KIRP_control.txt, KIRP_case.txt"
running pipeline: CPMI_KIRP.m

Information about the numerical simulation
running pipeline: CPMI_simulation.m


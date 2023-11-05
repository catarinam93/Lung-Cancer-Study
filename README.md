# ProjetoLabIACD_1

##  Dataset: LIDC - IDRI 
The LIDC-IDRI is a lung cancer screening dataset which comprises thoracic CT
scans for a total of 1010 patients, alongside with annotated nodules, made during a two-phase annotation
process by four experienced radiologists. The Dataset can be downloaded from this website https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI and contains standardized DICOM representation of the annotations and characterizations
collected by the LIDC/IDRI initiative, originally stored in XML

## Roadmap
- Preprocess LIDC dataset
    - Pre_Processing
        - pre-processamento.ipynb
    - Pre_Processing2
        - verifica.ipynb
        - pre_processing2.ipynb
- Feature_Extraction
  - Model_Training_Stats
      - Extração_features_radiomics.ipynb
      - Extração_features_xml.ipynb
      - Features_2d_+_diagnosis.ipynb
- Feature selection
  - Feature_Selection
      - feature_selection.ipynb
- Training and statistics
  - Treino_e_estatísticas
      - trainingmodelslast.ipynb

## Libraries
Libraries that need download - pandas, matplotlib.pyplot, seaborn, numpy, scikit-learn (sklearn), pylidc, radiomics, SimpleITK, scikit-image (skimage), scipy, pydicom

## References
- [AFMH+22] Jose Arimateia Batista Araujo-Filho, Maria Mayoral, Natally Horvat, Fernando Santini,
Peter Gibbs, and Michelle S Ginsberg. Radiogenomics in personalized management of
lung cancer patients: Where are we? Clinical Imaging, 2022.
- [AMB+15] Samuel G. Armato III, Geoffrey McLennan, Luc Bidaut, Michael F. McNitt-Gray,
Charles R. Meyer, Anthony P. Reeves, and L. P. Clarke. Data From LIDC-IDRI, 2015.
- [Ame19] American Cancer Society. Facts & Figures 2019. Technical report, 2019.
- [AMea11] Samuel G. Armato, Geoffrey McLennan, and et al. The Lung Image Database Consortium
(LIDC) and Image Database Resource Initiative (IDRI): A completed reference database
of lung nodules on CT scans. Medical Physics, 2011.
- [CZM+18] Jason L. Causey, Junyu Zhang, Shiqian Ma, Bo Jiang, Jake A. Qualls, David G. Politte,
Fred Prior, Shuzhong Zhang, and Xiuzhen Huang. Highly accurate model for prediction
of lung nodule malignancy with CT scans. Scientific Reports, 2018.
- [LG18] Bak SH Lee HY Lee G, Park H. Radiomics in Lung Cancer from Basic to Advanced:
Current Status and Future Directions. Korean J Radiol, 2018.
- [LLZ18] Lu Liu, Yapeng Liu, and Hongyuan Zhao. Benign and malignant solitary pulmonary nodules classification based on CNN and SVM. In ACM International Conference Proceeding
Series, 2018.
- [SZY+15] Wei Shen, Mu Zhou, Feng Yang, Caiyun Yang, and Jie Tian. Multi-scale convolutional
neural networks for lung nodule classification. In Lecture Notes in Computer Science
(including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics), 2015.
- [Tor23] et al. Torres, Guillermo. Prediction of Malignancy in Lung Cancer using several strategies
for the fusion of Multi-Channel Pyradiomics Images. In EasyChair - PrePrint), 2023.
4
- [Wor18] World Health Organisation. Latest global cancer data: Cancer burden rises to 18.1 million
new cases and 9.6 million cancer deaths in 2018. Int. Agency Res. Cancer, 2018.
[XZX+18] Yutong Xie, Jianpeng Zhang, Yong Xia, Michael Fulham, and Yanning Zhang. Fusing texture, shape and deep model-learned information at decision level for automated
classification of lung nodules on chest CT. Information Fusion, 2018

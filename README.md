![Alzihmer's Detection](https://github.com/Mourad9696/Alzehimer-s-ResNet50-MRI-Data/assets/99276310/3f34cc15-a815-43e5-97f5-1888db653e3d)




# Alzehimer-s-ResNet50-MRI-Data
Deep Learning-Based Automated Detection and Classification of Alzheimer's Disease Using Neuroimaging Data




Project Description:
This project focuses on the development of a deep learning-based system for automated detection and classification of Alzheimer's disease (AD) using neuroimaging data, specifically MRI scans. The goal is to provide an efficient and accurate tool for early diagnosis and classification of AD, which can greatly aid in timely intervention and treatment planning.

Key Features:

Neuroimaging Data Processing: The project includes a comprehensive pipeline for preprocessing and feature extraction from MRI scans. Various techniques such as image normalization, registration, and segmentation are employed to extract relevant features from the scans.

Deep Learning Model Selection: The ResNet50 architecture has been chosen as the primary deep learning model for classification due to its excellent performance in previous studies. ResNet50's ability to learn intricate patterns and its depth make it well-suited for the complex task of AD classification.

SHAP-Based Model Interpretability: The project incorporates the SHAP (SHapley Additive exPlanations) library to enhance model interpretability. SHAP values are used to quantify the contribution of each feature in the MRI scans towards the classification decision made by the ResNet50 model. This helps in understanding the importance and impact of different brain regions in the classification process.

Multi-Class Classification: The system is designed to classify MRI scans into four categories: 'CN' (cognitively normal), 'MCI' (mild cognitive impairment), 'LMCI' (late mild cognitive impairment), and 'AD' (Alzheimer's disease). The model is trained using labeled datasets with accurate ground truth labels.

Model Training and Evaluation: A rigorous training and evaluation process is followed to optimize the performance of the ResNet50 model. The training dataset is utilized to train the model, and the testing dataset is used for evaluating its accuracy, precision, recall, and F1-score.

ADNI Dataset: The study utilizes the ADNI (Alzheimer's Disease Neuroimaging Initiative) dataset, a widely used and publicly available dataset for Alzheimer's research. The inclusion of this dataset enhances the generalizability and validity of the findings.

Open-Source and Reproducible: The entire project, including the codebase, pre-trained models, labeled datasets, and SHAP-based interpretability methods, is made available as an open-source resource on GitHub. Users are encouraged to freely use and modify the provided code for their own research purposes.

Code Usage and Contact Information: Users are welcome to use the codes provided in the repository. For any inquiries, further information, or collaboration opportunities, please don't hesitate to contact the project author at m.mourad9696@gmail.com.

This project aims to contribute to the ongoing research in Alzheimer's disease detection and classification by providing a robust and accurate deep learning-based solution. The inclusion of the SHAP library enhances the interpretability of the model, offering insights into the underlying features driving the classification decisions. The automated system, using the ADNI dataset, has the potential to assist healthcare professionals in making informed decisions and improve the early diagnosis and management of Alzheimer's disease.

SHAP Results example:
![SHAP](https://github.com/Mourad9696/Alzehimer-s-ResNet50-MRI-Data/assets/99276310/8c7ef5e1-50d4-446b-9a80-5a519edde22b)

Patient Sample:
![Sample](https://github.com/Mourad9696/Alzehimer-s-ResNet50-MRI-Data/assets/99276310/c72299f5-0b60-4a78-8b8b-f0298a915f83)


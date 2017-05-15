### Convolutional Neural Network-based Model for Patient Representation Learning to Uncover Temporal Phenotypes for Heart Failure

Yichen Shen Chongchao Zhao Li-Pan Yao

Electronic Health Records (EHR) are immense datasets filled with a wealth of all kinds of medical data for each patient for each medical visit. However, traditional methods of data analysis on EHR datasets prove impenetrable due to its size, dimensionality, and irregularity. Heart failure (HF) has frustrated caregivers due to difficulty in prediction as well as its nature as an overarching condition rather than a distinct phenotype. In this work, we propose to utilize convolutional neural networks (CNN) on EHR data, which would allow us to precisely predict risks of heart failure and efficiently extract informative representations of HF patients. The representation can help identify a new set of phenotypes with similar EHR profiles to facilitate treatment of patients with HF.



Usage:

Initial_data_preprocessing.ipynb -> load the data from raw mimic files to get all events for each patient

Create_date_token_feature.ipynb -> padding time token features into patients' event data

train_word2vec.ipynb -> train word2vec model using events data

filter_and_contruct_patient_groups.ipynb -> divide patients and filter out patients with legit amount of data/contruct demographic features

processingData * -> load the data and construct features for baseline models
baselineModels * -> train baseline prediction models

setup_train_visualize_cnn.ipynb => main body of the analysis

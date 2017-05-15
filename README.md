Computational Phenotyping with HF patients using CNN

Initial_data_preprocessing.ipynb -> load the data from raw mimic files to get all events for each patient

Create_date_token_feature.ipynb -> padding time token features into patients' event data

train_word2vec.ipynb -> train word2vec model using events data

filter_and_contruct_patient_groups.ipynb -> divide patients and filter out patients with legit amount of data/contruct demographic features

processingData * -> load the data and construct features for baseline models
baselineModels * -> train baseline prediction models

setup_train_visualize_cnn.ipynb => main body of the analysis

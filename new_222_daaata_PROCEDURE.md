
1.  Original:    
        new_222_data_original.csv
            average of MBD and covariates over 12 months

2.  Cleaned:     
        new_222_data_cleaned_full.csv
            delete features with 10%+ missing data
            delete rows where MBD == NaN 
            delete rows where MBD == 0

3.  Cleaned & Train Test Split:
        new_222_data_cleaned_train.csv
        new_222_data_cleaned_test.csv
            train-test-split: 80-20
            NOTE: EVERYTHING BELOW IS DONE WITH CLEANED DATASET

4.  Imputed:
        new_222_data_train_imputed.csv
        new_222_data_test_imputed.csv
            imputed with KNN imputer fitted on the trainset

5.  Normalized:
        new_222_data_train_norm.csv
        new_222_data_test_norm.csv
            normalized by subtracting the train mean 
            and deviding by train standard deviation

6.  De-correlated:
        new_222_data_train_decorr.csv
        new_222_data_test_decorr.csv
            clustered correlatated features with k-means
            performed PCA on each cluster for N PCs
            replaced correlatated features with their PCs

7.  De-correlated & Imputed:
        new_222_data_train_decorr_imputed.csv
        new_222_data_test_decorr_imputed.csv
            KNN imputation for missing values

7.  De-correlated & Imputed & Normalized:
        new_222_data_train_norm_decorr.csv
        new_222_data_test_norm_decorr.csv




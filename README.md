# Coffee churn model artifacts

This repository contains the trained LogisticRegression pipeline and its run configuration for the Yandex Practicum coffee delivery churn project. The pipeline includes feature generation, imputation, scaling, categorical encoding, feature selection, and classification.

## Files

- `coffee_churn_pipeline.joblib` — fitted end-to-end pipeline.
- `coffee_churn_config.joblib` — selected features, hyperparameters, and evaluation metrics.
- `requirements.txt` — package versions used when the artifacts were created.

The public source dataset is available from Yandex Practicum: https://code.s3.yandex.net/datasets/coffee_churn_dataset.csv. The dataset itself is not included here.

The artifact was created with scikit-learn 1.7.2. For loading a joblib model, use the compatible package versions listed in `requirements.txt`.

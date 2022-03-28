# msd_pred_fe_conc

Description:

Project to obtain a regression model for %Fe in iron magnetic concentrates, Santo Domingo, Capstone.

Final archives:

- data preparation and base model: data_preparation_msd_v02_final.ipynb

    EDA: EDA.ipynb
    EDA considered "X_y_preproc.csv", which includes preprocessed features (including OHE of categorical features) and predicted target.

- modeling, model tuning and final prediction: model_tuning_&_prediction_v01.ipynb
    Considered 'X-Copy1.csv', with final feature selection (after some features were removed).

- data preparation for drillholes data base: data_prep_drillholes.ipynb
    Condidered 'DB_Prediction_filtered.csv'. The latter was prepared from Leapfrog merged archive, with the following row deletion criteria:
    1. Rows witn no ICP
    2. Rows with no MS_Actual (magsus)



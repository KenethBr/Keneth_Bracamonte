| modelo | train_time_s | test_time_s | accuracy | precision_macro | recall_macro | f1_macro | auc_ovr_macro | saved_model_path |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| RandomForest | 1.775 | 0.049 | 0.9118 | 0.9253 | 0.8856 | 0.9008 | 0.987618 | models\RandomForest_final.joblib |
| KNN | 0.036 | 0.365 | 0.9073 | 0.9205 | 0.9005 | 0.9079 | 0.946595 | models\KNN_final.joblib |
| LogisticRegression | 2.478 | 0.005 | 0.8920 | 0.8735 | 0.8972 | 0.8828 | 0.970602 | models\LogisticRegression_final.joblib |
| SVM | 2.799 | 0.064 | 0.8839 | 0.8737 | 0.8902 | 0.8810 | 0.956739 | models\SVM_final.joblib |
| DecisionTree | 0.336 | 0.003 | 0.7795 | 0.7739 | 0.7921 | 0.7761 | 0.887806 | models\DecisionTree_final.joblib |
| GaussianNB | 0.152 | 0.029 | 0.7759 | 0.6968 | 0.7999 | 0.7170 | 0.936128 | models\GaussianNB_final.joblib |

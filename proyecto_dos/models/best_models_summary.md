| Modelo | Hiperparámetros óptimos |
|---|---|
| K-Nearest Neighbors (KNN) | n_neighbors=3, weights='distance', metric='euclidean' |
| Gaussian Naive Bayes | var_smoothing=np.float64(0.01) |
| Regresión Logística | clf__C=np.float64(32.90344562312671), clf__penalty='l2', clf__solver='lbfgs' |
| Árbol de Decisión | criterion='entropy', min_samples_split=np.int64(7), min_samples_leaf=np.int64(3), splitter='random', max_depth=None |
| Support Vector Machines (SVM) | C=0.1, kernel='linear', gamma='scale' |
| Random Forest | n_estimators=300, max_depth=40, max_features='sqrt', criterion='gini', bootstrap=False, min_samples_split=2, min_samples_leaf=1 |

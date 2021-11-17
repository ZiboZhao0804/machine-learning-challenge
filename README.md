# machine-learning-challenge

## The following features are selected:
'koi_fpflag_nt', 'koi_fpflag_ss', 'koi_fpflag_co','koi_fpflag_ec', 'koi_period', 'koi_time0bk', 'koi_impact','koi_duration', 'koi_depth', 'koi_prad', 'koi_teq', 'koi_insol', 'koi_model_snr', 'koi_tce_plnt_num', 'koi_steff',  'koi_slogg', 'koi_srad',  'ra', 'dec','koi_kepmag'
## Test size of 0.2 is used for all model.
## Top important features
- koi_model_snr
- koi_fpflag_nt
- koi_fpflag_co
- koi_fpflag_ss
## The following models were applied:
- [Decision Tree](model_DecisionTree.ipynb), test score: 0.843
- [Random Forest](model_RandomForest.ipynb), n_estimators=1000, test score: 0.898
- [K Neearest Neighbors (KNN)](model_KNN.ipynb), feature columns are scaled, n=11, test score: 0.786
- [Support Vector Machine (SVM)](model_SVM.ipynb), test score: 0.761
- [Neural Network](model_NeuralNetwork.ipynb), 1 hidden layer wth 100 units, epochs = 150, test score: 0.865
- [Deep Learning](model_DeepLearning.ipynb), 2 hidden layers with 100 units each, epochs = 150,test score: 0.872
## Best model is random forest!
- Hyper Parameter Tuning is further performed and the test score is 0.900 <br>
**{'bootstrap': True,
 'max_depth': 100,
 'max_features': 3,
 'min_samples_leaf': 3,
 'min_samples_split': 8,
 'n_estimators': 200}**

- [Random Forest model](model_RandomForest.sav)
## Deep learning also works fine.
- [Deep Learning model](model_DeepLearning.h5)


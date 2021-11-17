# machine-learning-challenge

## The following features are selected:
'koi_fpflag_nt', 'koi_fpflag_ss', 'koi_fpflag_co','koi_fpflag_ec', 'koi_period', 'koi_time0bk', 'koi_impact','koi_duration', 'koi_depth', 'koi_prad', 'koi_teq', 'koi_insol', 'koi_model_snr', 'koi_tce_plnt_num', 'koi_steff',  'koi_slogg', 'koi_srad',  'ra', 'dec','koi_kepmag'
## Test size of 0.2 is used for all model.
## The following models were applied:
- Decision Tree (model_DecisionTree.ipynb), test score: 0.843
- Random Forest, test score: 0.905
- K Neearest Neighbors (KNN) (feature columns are scaled),test score: 0.793, n=15
- Support Vector Machine (SVM), test score: 0.775

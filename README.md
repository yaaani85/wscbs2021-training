# Train 
This is an example Brane package to train a ML model. Import it as follows:

```shell
$ brane import onnovalkering/train
```

The following ENVIRONMENT variables could be set: 

```shell
$ export MODEL_NAME='lightgbm' 
$ export EVAL_METRIC='auc' 
$ export MAX_DEPTH=1 
$ export N_ESTIMATORS=30000 
$ export LEARNING_RATE=0.05 
$ export NUM_LEAVES=4095 
$ export COLSAMPLE_BYTREE=0.28 
$ export OBJECTIVE='binary' 
$ export USE_LOCAL=True 
$ export USE_SAMPLED_DATA=True
```

# FlowDrive Training and Evaluation

## 1. Cache dataset for training and evaluation

```
# cache dataset for training
python navsim/planning/script/run_dataset_caching.py agent=flowdrive_agent experiment_name=trainingflowdrive_agent train_test_split=navtrain

# cache dataset for evaluation
python navsim/planning/script/run_metric_caching.py train_test_split=navtest cache.cache_path=$NAVSIM_EXP_ROOT/metric_cache
```
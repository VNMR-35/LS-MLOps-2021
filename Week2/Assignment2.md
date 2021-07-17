[Week 2 Assignment](https://github.com/VNMR-35/MLOps_Assignment)
## List of commands:
Git cloning was done through GitHub desktop.
* `dvc init`
* `mkdir data`
* `dvc cache dir ../external_cache`
* `dvc add data/creditcard.csv`
* `git add data/creditcard.csv.dvc data/.gitignore`
* `git commit -m "Add raw data"`
* `dvc remote add -d storage s3://mlopsassignment190010070/datastore`
* `git add .dvc/config`
* `git commit -m "Configure remote storage"`
* `dvc push -v`
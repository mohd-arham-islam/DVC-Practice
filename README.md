## DVC Practice
DVC -> Data Version Control

If we have a very large dataset, of maybe in GBs, then we can't track it using Git. This is where DVC helps us to do version control for our data.

`dvc init` -> to initialize DVC

`dvc data/data.csv` -> To add the file to staging area.

`git log` -> To checkout the logs

`git checkout <Commit ID>` -> To move to this commit

`dvc checkout <Commit ID>` -> To move to this data commit
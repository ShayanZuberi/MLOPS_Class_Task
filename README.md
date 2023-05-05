# DVC Demo - Steps
1) Create a repository on GitHub with master branch
2) Select some big dataset from Kaggle or anyother of your liking (atleast 100MB size)
3) Create a remote drive (google drive, S3, etc)
4) Clone the repo on your local machine and track it using dvc
5) push the dataset (locally present) using dvc
6) Create train.py for training some  ML technique (using sklearn) on the given data set
7) Create DVC pipeline to create a metrics.json file. track it using dvc. Use GithubActions to automate the execution of the dvc pipeline.
8) Edit the train.py file and use some other ML technique. Create a pull request with the new file.
9) Compare the results like we did in the class and merge the branches if the results are better.

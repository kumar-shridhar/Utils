# Utils
* CSV to JSON file converter
* Augment text dataset using synonyms
* Split test train

### Command to copy 10 files from one dir to another
* ls -Q dir1 | shuf -n -10 | xargs -i mv dir1/{} dir2/

### Set Ipython/Jupyter Kernel
* python -m ipykernel install --user --name myenv --display-name "Python (myenv)"

### Put large files in gitignore in GitHub
* find ./* -size +100M | cat >> .gitignore

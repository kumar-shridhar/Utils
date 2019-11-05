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

### Check Graphics card presence
* lspci | grep VGA

### Cut n lines from one file to the other
* head -n file_to_copy_from > file_to copy to && sed -i '1,+n-1d' file_to_copy_from
  * Example: head -100000 OpenSubtitles.de-en.de > OpenSubtitles.de-en.de.valid && sed -i '1,+99999d' OpenSubtitles.de-en.de

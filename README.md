Creating a env
``` bash
conda create -n wineq
```

Activating env
``` bash 
conda activate wineq
```

Created requirements.txt file and Install the requirements.txt file 
``` bash
pip install -r requirements.txt
```

Initialize the git 
```bash 
git init
```

Install dvc and Intializing the dvc 
```bash
conda install -c conda-forge dvc
```
```
dvc init
```

git adding all
```bash
git add .
```
git commiting changes here
```bash
git commit -m "first commit"
```
update for readme file
```bash
git commit -m "updated README.md"
```

```bash
git remote add origin https://github.com/Muragunde/winequality_project.git
git branch -M main
 git push -u origin main
 ```
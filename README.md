Create environment
```bash
2  conda create -n wineq python=3.7 -y
```
Activate env
```bash
conda activate wineq
```

Create and install requirements.txt file
```bash
touch requirements.txt
pip install -r requirements.txt
```

git init

dvc init

dvc add data_given/winequality.csv

git add .
git commit -m "first commit"

One line update README.md

git add . && git commit -m "update Readme.md"
git remote add origin https://github.com/alexfrank10/dvc-demo.git
git branch -M main

git push -u origin main

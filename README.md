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
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```
```bash
git commit -m "first commit"
```

One line update README.md
```bash
git add . && git commit -m "update Readme.md"
```
```bash
git remote add origin https://github.com/alexfrank10/dvc-demo.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
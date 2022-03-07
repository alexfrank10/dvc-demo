Create environment
```bash
2  conda create -n wineq python=3.7 -y
```
Activate env
```bash
conda activate wineq
```
Download data
```bash
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec
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
git branch -M main
git push -u origin main
```

tox command
```bash
tox
```

for rebuilding
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup command
```bash
pip install -e .
```

build your own package
```bash
python setup.py sdist bdist_wheel
```

one command line to commit and push
```bash
git add . && git commit -m "setup done" && git push origin main
```
Create environment
"""bash
2  conda create -n wineq python=3.7 -y
"""
Activate env
"""bash
conda activate wineq
"""

Create and install requirements.txt file
"""bash
touch requirements.txt
pip install -r requirements.txt
"""

git init

dvc init

dvc add data_given/winequality.csv
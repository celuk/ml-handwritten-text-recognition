# handwriting-text-recognition

Grup-18

Seyyid Hikmet Çelik

221111033

## Running

Create a conda environment and install dependencies:

```bash
conda create -n tfenv python=3.10
conda activate tfenv
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
python -m pip install --upgrade pip
pip install tensorflow==2.10
pip install pandas
pip install matplotlib
pip install seaborn
pip install opencv-python
pip install scikit-learn
pip install notebook==6.5.6
pip install imutils
conda install -c conda-forge pandoc
pip install opencv-contrib-python --user
```

then run jupyter-notebooks:

```bash
conda activate tfenv
jupyter-notebook
```

Before that for datasets;

(Datasets just a small part exists in the repo because of couldn't upload all of them.)

Download and extract https://www.kaggle.com/datasets/landlord/handwriting-recognition dataset into `handwriting-recognition` folder.

Download and extract https://www.kaggle.com/datasets/nibinv23/iam-handwriting-word-database dataset into `iam-handwriting-word-database` folder.

Reach other models' h5 files from here (couldn't upload to github because of maximum file size (100MB)): https://etuedutr-my.sharepoint.com/:f:/g/personal/seyyidhikmetcelik_etu_edu_tr/Eoq9hmts_iFDpngQxTk4AaIBcoAf55-354bAe2UmiEQL2w?e=iK10Up

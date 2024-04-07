# handwriting-text-recognition

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

then run jupyter-notebooks.

Before that for datasets;

Download and extract https://www.kaggle.com/datasets/landlord/handwriting-recognition dataset into `handwriting-recognition` folder.

Download and extract https://www.kaggle.com/datasets/nibinv23/iam-handwriting-word-database dataset into `iam-handwriting-word-database` folder.


Assignment 1: Supervised Learning

Link to code and data https://github.com/bkashyap/CS7641_Asst1_submission/

There are two jupyter-notebooks:
1. WineQuality.ipynb - contains all analysis for first dataset Wine Quality.
    It leverages two csv files from https://archive.ics.uci.edu/ml/datasets/Wine that the code combines:
    1. winequality-red.csv
    2. winequality-white.csv
2. BreastCancer.ipynb - contains all analysis for second dataset Breast Cancer.
    Data is in BreastCancer.csv which comes from https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

Since all analysis is done in Jupyter IPython Notebooks you should be able to see the charts and code by just opening the files in github. Here are the direct links
1. Wine Quality - https://github.com/bkashyap/CS7641_Asst1_submission/blob/master/WineQuality.ipynb
2. Breast cancer - https://github.com/bkashyap/CS7641_Asst1_submission/blob/master/BreastCancer.ipynb

Code used from external sources have been referenced in the comments.

Here is the link to the entire repository containing the data and notebooks: https://github.com/bkashyap/CS7641_Asst1_submission

How to run:
1. Clone repository from github:https://github.com/bkashyap/CS7641_Asst1_submission
2. requirements.txt contains all dependencies (The major ones are pandas, numpy, jupyter, seaborn, matplotlib). Create Conda Python3 environment using requirements.txt by running conda install --name asst1 --file requirements.txt
3. Run jupyter-notebook
4. Open localhost:8888 on your browser and navigate and open WineQuality.ipynb or BreastCancer.ipynb
5. If you need to run the code you can run individual code blocks by pressing shift + enter

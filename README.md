To run the notebook, follow the instructions below for Windows:

1. Install miniconda https://docs.conda.io/en/latest/miniconda.html

2. Open miniconda terminal. All steps below are typed in the terminal.

3. Install Jupyter Notebook in terminal:
conda install jupyter notebook

3b. If there is an error with step 4, this step is required. Find these two files in anaconda3>Library>bin:
libcrypto-1_1-x64.dll libssl-1_1-x64.dll and then copy and paste it to anaconda3>DLLs. Restart the pc.

Refer to here if the issue persists:
https://github.com/conda/conda/issues/11982

4. Install pytorch:
conda install pytorch torchvision -c pytorch

5. Install fast ai:
conda install -c pytorch -c fastai fastai=1.0.61
conda install -c fastai fastdownload

6. Install dependencies:
pip install -U duckduckgo_search
conda install fastbook -c fastai
pip install fastcore fastai --upgrade

7. Open Jupyter Notebook through terminal:
jupyter notebook

8. The notebook should run now.
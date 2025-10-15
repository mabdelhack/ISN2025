File location to download:

https://drive.google.com/file/d/1xaELC32GasXlpQur51o9ga9sIQ76JHA4/view?usp=sharing

Download and extract inside the repository so you have a second folder called FaceRecognition


### Open Notebooks in Jupyter Lab
This involves running the *ipynb python notebooks in Jupyter Lab running in a Browser. Then you can run cells, edit code, change outputs, etc.

For this, you need to install Miniconda and JupyterLab as explained below. However, unless you are running Unix/Linux(WSL)/MacOS, you will not be able to run the Apptainers used in Notebook 03 (nb03) - for this you need Option 3 below.

Install Miniconda from here: https://docs.anaconda.com/miniconda/

Open an “Anaconda Powershell Prompt (miniconda3)” terminal

Change to the local directory where you downloaded everything  (using “cd” command).

Type conda env create -f mri_environment.yml to create your python environment.

Install Jupyter Lab with conda install -c conda-forge jupyterlab

Once above packages installed, each time you want to start a notebook from your terminal:

Type conda activate mri

Type jupyter lab. This will either open your default browser with Jupyter Lab running in a tab, or if it cannot, then it will provide a URL that you can copy and paste into a browser that you open yourself.

From Jupyter Lab, open the relevant notebook(s) from the File menu, eg from the local directory where you downloaded the notebooks. Jupyter Lab is fairly intuitive.

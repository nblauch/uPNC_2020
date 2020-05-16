# uPNC_2020
Welcome to the GitHub page for the Summer 2020 undergraduate Program in Neural Computation at the Center for the Neural Basis of Cognition, University of Pittsburgh and Carnegie Mellon University.
## Setup
Throughout the 2 week bootcamp introduction to the program, we will be doing computational exercises to go along with the faculty research lectures. We have tried to make most of them in Python, which we believe is the best single language for computational neuroscience in 2020. Python is an object-oriented language with great strengths in scientific computing, including incredible packages for neuroimaging, psychophysical experimentation, and machine learning. 

Python code can be written and executed in a variety of ways:
  - Arbitrary text editor (e.g. VIM, Atom) + standard unix terminal
  - Integrated Development Environment (IDE), e.g. Spyder or PyCharm
  - Jupyter Notebooks locally through regular Jupyter Notebooks or JupyterLab (which has many more features and many of the benefits of an IDE)
  - Jupyter Notebooks remotely, through regular Jupyter Notebooks, JupyterLab, JupyterHub, Google Colab Notebooks, Binder, etc.
  
  It is up to you how you write and execute your code. However we encourage you to use Jupyter Notebooks through JupyterLab locally on your personal machine. We will also show you how to set up a JupyterLab server on a remote computing cluster (e.g. the CNBC MIND cluster), which may be very useful for your summer research if you end up requiring serious computing power. We also highly encourage you to use the Anaconda distribution of Python, which ships with many scientific packages, the Spyder IDE, and jupyter notebooks installed, along with its most important feature - the `conda` package manager. 
  
### Step 1: Install Anaconda
Follow [these instructions](https://docs.anaconda.com/anaconda/install/)
Miniconda is the better choice for people who do not have a lot of available disk space. You can always download the rest of the packages later with `conda install` or `pip install`.

### Step 1b. Verify your installation
Make sure that your installation is working. Open the Anaconda Application and try to launch the Spyder IDE or a local Jupyter Notebooks server. 

Now open up a terminal (Mac or Linux) or Anaconda command prompt (Windows).
```bash
# check that your system is now using Anaconda's python
which python

# and that you installed Python 3.7
python -V
```
Don't worry too much about the version - it's good to have your base install have the newest version of Python, but you can always create virtual environments later with earlier versions of Python to, e.g., build upon someone else's code which is only compatible with earlier versions (e.g. Python 2.7, how are people still using this??)

### Step 2: Install JupyterLab
Within your teminal/command prompt, you now have access to the conda package manager. You should read up about it [here](https://docs.conda.io/projects/conda/en/latest/index.html)
Use conda to install Jupyterlab:
```bash
# jupyterlab is located on the conda-forge channel, along with many other packages
conda install -c conda-forge jupyterlab
```

### Step 3: Launch a local JupyterLab server

### Step 3b (bonus): Set up a remote JupyterLab server

### Step 4: Create a conda virtual environment 

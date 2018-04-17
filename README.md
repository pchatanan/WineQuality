

# Wine Quality Prediction - Machine Learning

 This project is part of **NTU CE9010 Course Project**.
 
## Get started

### Requirements

- This project works on **Python 3.6.x 64-bit** version.

If you want to train neural network, you need to install the following requirement below. Otherwise, you do not need these requirements.

1. Tensorflow with GPU support - [follow this instruction](https://www.tensorflow.org/install/install_windows)

### Create virtual environment

 1. Install `virtualenv` package:
    
    > pip install virtualenv

 2. Create virtual environment

    > virtualenv venv

 3. Activate the created virtual environment

     - Using Git Bash (reccommended):
 
    > . venv/Scripts/activate

    - Using Command Prompt:
 
    > venv\Scripts\activate.bat
  
 4. Install requirements:

    -  If Tensorflow is installed with GPU suport:
 
    > pip install -r requirements.txt
    
    - else:

    > pip install -r light-requirements.txt

### Run Jupyter Notebook

#### Windows:

 1. Double click `start.bat`. Default browser should be opened with Jupyter Notebook.
 2. Open `./src/AllState.ipynb`

#### Other OS:

 1. Activate virtualenv
 2. Use command:
    > jupyter notebook
    
    Default browser should be opened with Jupyter Notebook.
 3. Open `./src/AllState.ipynb`

### View Notebook in HTML without running code:
- html files are available in `./html` folder
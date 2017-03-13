CosmoSim Jupyter Notebooks for UWS with Python
==============================================

This repository is a collection of Jupyter Notebooks which explain how to work with the [CosmoSim database](https://www.cosmsim.org/) of cosmological simulation data and its UWS interface.


## Requirements:
- python 2 
    - virtualenv
    - astropy
    - matplotlib, mpl_toolkits  
      (you may need to install `python-tk` on your system, first)
    - uws-client
- git
- a user account at https://www.cosmsim.org/

You can use the demo user account as well (credentials are given in the notebook), but anyone could interfere at any time and delete your data. Thus it's recommended and more fun to have your own user account.


## Installation of the notebook:
* Clone this git repository:
    ```
    git clone https://github.com/kristinriebe/cosmosim-uws-notebook.git
    ```

* Create a virtual environment (must be python 2.7):
    ```
    virtualenv -p /usr/bin/python2.7 venv
    ```

* Activate the virtual environment:
    ```
    source venv/bin/activate
    ```

* Install all required packages:
    ```
    pip install -r requirements.txt
    ```


## Run the notebook

* Start the notebook server:
    ```
    jupyter notebook
    ```

* Select a notebook file (`*.ipynb`) and click on it to start it.

* Go through each field and run it using `Shift`+`Enter`.

* That's it! Go ahead and enjoy!

# L1. Dead Reckoning
In this lab session we are going to experiment with the use of a dead reckoning transition model for localization. The main goal of the session is to generate three different metrics to evaluate the localization performance, and to execute several experiments sequentialy.

------------------------------------
## 1. Set up
### In case of initial setup

#### Clone the repository

    $ cd
    $ mkdir lib
    $ cd lib
    $ git clone git@github.com:ericguerrero/11765_MUSI.git

#### Set python environment
Go to the repository directory and execute next commands.

    $ python3 -m venv env
    $ source env/bin/activate
    $ python3 -m pip install -r requirements.txt

In case you need extra packages install them using the following command.

    $ python3 -m pip install **name_of_a_packacge_you_need**


### Update the repository
Go to your local repository directory, commit your changes and syncronize with the remote repository on github. 

    $ cd
    $ cd lib/11765_MUSI
    $ git commit -m "add lab0"
    $ git pull

### Source the python environment
Now, in order to be able to import dependecies, source the python environment.

    $ source env/bin/activate

### Open the jupyter notebook
Launch the jupyter notebook using the following command:

    $ jupyter-lab

In case that this command does not open a new tab in your browser you can copy the URL and paste it manualy in the browser.
Moreover, if the notebook does not load properly, you can try running the next command:

    $ jupyter lab

------------------------------------
## 2. Open the Lab1 notebook
Once inside jupyter notebook go to the notebooks directory using the menu at the left of the screen and open the Lab1.ipynb file. Go through the notebook and complete the three described tasks 


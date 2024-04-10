# Data Scientist Challenge

## Higher Education Students Performance Evaluation

This project focuses on analyzing student behavior and study patterns with specific objectives. It aims to explore demographic characteristics associated with test success, evaluate study effectiveness, uncover dataset trends, and provide insightful analyses on their implications.


The data was collected from the Faculty of Engineering and Faculty of Educational Sciences students in 2019 and donated to [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/856/higher+education+students+performance+evaluation) . The purpose is to predict students' end-of-term performances using ML techniques.
  
## Setup

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activating your newly created environment 
* upgrading `pip` (This step is not absolutely necessary, but will save you trouble when installing some packages.)
* installing the required packages via `pip`


Please, check before that you met the requirements

```bash
pip freeze > requirements.txt
```

## Installing the enviroment  
### **`MacOS`** type the following commands :
```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python.exe -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python.exe -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:
    ```Bash
    'python.exe -m pip install --upgrade pip'
    ```

In order to upgrade all packages in requirements.txt you can `pip install upgrade-requirements`
and then run: `upgrade-requirements`.
This will also automatically update the requirements.txt document. (Works only with pinned (`==`) packages at the moment.)
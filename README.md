# Machine Learning Projects

## PROJECT CHECKLIST
1. _Frame the Problem & Look at Big Picture_
2. _Get the Data_
3. _Explore the Data_
4. _Prepare the Data_
5. _Shortlist Promising Models_
6. _Fine-Tune the System_
7. _Present Your Solution_
8. _Launch!_

## STEPS
```python
# create workspace directory
$ export ML_PATH = "$HOME/ml"		# custom
$ mkdir -p $ML_PATH
```
```python
# check if pip installed
$ python3 -m pip --version
# upgrade pip module
$ pyhton3 -m pip install --user -U pip
```
```python
# install virtualenv
$ python3 -m pip install --user -U virtualenv
# create isolated environment
$ cd $ML_PATH
$ virtualenv my_env

# activate this environment
$ cd $ML_PATH
$ source my_env/bin/activate		# deactivate
```
```python
# install all 
$ python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
# check installation
$ python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn"
# launch jupyter
$ jupyter notebook
```

# virtualenv

### 1. install virtualenv:
    pip install virtualenv
    # check virtualenv version
    virtualenv --version
    
### 2. create virtual env for project with specific python version:
    virtualenv -p /usr/bin/python2.7 my_project
    
### 3. start virtual env:
    source my_project/bin/activate
   
### 4. install numpy, pandas, scikit-learn
    pip install -U scikit-learn 
    pip install numpy
    pip install scipy
    pip install matplotlib
    pip install pandas
    
### 5. install tensorflow 1.2
    pip install tensorflow==1.2.0rc0

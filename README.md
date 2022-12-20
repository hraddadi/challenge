# Challenge
'''This is going to be a significant challenge.''
'''Well, this challenge has three areas to measure my skills. The first one is about Data Science technical skills, and the second and the third challenges are about "Technical writing" and personal questions that will help me get to know myself.

### 1. Data Science Technical Skills:
'''I am using [Ubuntu OS 20.04](https://ubuntu.com/).
'''So, we will create a workspace for our machine learning project.
'''Go to the terminal and type the following commands:''
```sh
$ export ML_PATH= "$HOME/ml"      #you can change the path if you prefer
$ mkdir -p $ML_PATH
```
```sh
$ python3 -m pip install --user -U pip
```
Creating an isolated environment
install virtualenv by running the following pip command
```sh
$ python3 -m pip install --user -U virtualenv
```
Now we can create an isolated Python environment by typing this:
```sh
$ cd $ML_PATH
$ virtualenv my_env
```
Now every time you want to activate this environment, just open a terminal and type the following:
```sh
$ cd $ML_PATH
$ source my_env/bin/activate
```
Now you can install all the required modules and their dependencies using this simple pip command:
```sh
$ python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn
```
Now install [requirements.txt](https://github.com/hraddadi/challenge/blob/main/technical_skills/requirements.txt)
```sah
$ pip install -r requirements.txt
```
Now the environment is ready.

- [Dataset](https://www.kaggle.com/datasets/aadityasinghal/facial-expression-dataset)

- [The Final Model](https://mega.nz/file/6d91BA6Q#ifD0xpkkU2CrZnuXLLqGHHVP_zoXAMIJ0tE8TufDecc)

- [The Solution](https://github.com/hraddadi/challenge/blob/main/technical_skills/facial-expression.ipynb)

![alt text](https://github.com/hraddadi/challenge/blob/main/technical_skills/machine_test.png)

### 2.Technical Writing and Design
[summary for An Introduction to Convolutional Neural Networks](https://github.com/hraddadi/challenge/blob/main/Summary%20for%20a%20research%20paper.pdf)

[The Research Paper](https://github.com/hraddadi/challenge/blob/main/An%20Introduction%20to%20Convolutional%20Neural%20Networks.pdf)

### 3.Personal Questions
[PDF File](https://github.com/hraddadi/challenge/blob/main/Personal.pdf)

---
title: Virtual Environments
duration: "1:00"
creator:
    name: Pauline Chow
    city: LA
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Introduction to Virtual Environments
Week 8 | Lesson 2.3

### LEARNING OBJECTIVES
*After this lesson, you will be able to:*
- under virtual environment for python
- learn how to effectively use virtual environments
- create and destroy virtual environments in your local environments
- save and pipe your environment to requirements.txt

### STUDENT PRE-WORK
*Before this lesson, you should already be able to:*
- install packages in their local environment
- open and interact with the terminal
- understand the file system on their machines

### INSTRUCTOR PREP
*Before this lesson, instructors will need to:*
- Generate a brief slide deck
- Prepare any specific materials
- Provide students with additional resources


### LESSON GUIDE
| TIMING  | TYPE  | TOPIC  |
|:-:|---|---|
| 5 min | [Opening](#opening) | Opening |
| 5 min | [Introduction](#intro-venv) | What are Virtual Environments?|
| 10 min | [Guided Practice](#why-venv) | Why virutal environments? |
| 10 min | [Demo](#types-venv) | How to Use Virtual Environments?|
| 10 min | [Guided Practice](#venv-wrappers) | Virtual Environments wrappers |
| 15 min | [Independent Practice](#venv-save-load) | Portable Virtual Environments - Save and Load Configruations|
| 5 min | [Conclusion](#conclusion) | Conclusion |

<a name="opening"></a>
# Opening 

<a name="introduction"></a>
# Introduction - What are Virtual Environments?

<a name="why-venv"></a>
# Why Virtual Environments? Use Case

A Virtual Environment is a tool to keep the dependencies required by different projects in separate places, by creating virtual Python environments for them. It solves the “Project X depends on version 1.x but, Project Y needs 4.x” dilemma, and keeps your global site-packages directory clean and manageable.

For example, you can work on a project which requires Django 1.3 while also maintaining a project which requires Django 1.0.

[Python Docs](http://docs.python-guide.org/en/latest/dev/virtualenvs/)

<a name="types-venv"></a>
# How to Use Virtual Environments?

## Package Managers

virtual environment package for python is available through *pip* and *conda* package managers. [comparison between pip and conda virtualenv](http://conda.pydata.org/docs/_downloads/conda-pip-virtualenv-translator.html)

install through pip package manager
```bash
pip install virtualenv
```
install through conda package manager
```bash
conda install virtualenv
```
## Create virtual environments

create new environments through pip package manager
```bash
cd $ENV_BASE_DIR
virtualenv $ENVIRONMENT_NAME
```
create new environments through conda package manager
```bash
conda create --name $ENVIRONMENT_NAME python
```

## Activate and deactive virtual environments

start environments through pip package manager
```bash
source $ENVIRONMENT_NAME/bin/activate
```
start environments through conda package manager
```bash
source activate $ENVIRONMENT_NAME
```

<a name="venv-save-load"></a>
# Portable Virtual Environments

<a name="conclusions"></a>


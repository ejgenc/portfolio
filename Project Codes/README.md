# Hello there!

## This repository holds the codes for each of my data analysis and visualizations projects. For my portfolio that explains these projects, please [refer to this link.](https://ejgenc.github.io/portfolio/) You can also look at individual folders to see source code / a little bit of explanation.

# {{cookiecutter.project_name}} #

![Header]()

* * *

## External Links ##

Lorem dolor ipsum sit amet

## What is this project about? ##

{{cookiecutter.description}}

## Technical Details ##

Lorem Dolor Ipsum Sit Amet

* * *

## How to reproduce this project? ##

### Why reproducibility? ###

I believe that openness and ease of reproduction are two very important concepts that builds a foundation of trust under the dissemination of knowledge. You can always consume the end result of my project, that is what most people do. However, there may be people who want to be able to re-create my analysis steps one by one. This is the reason why this project was built with reproducibility in mind.

### Methods of reproduction ###

Succesful reproduction of a data science/analysis projects requires the communication of the information that is related to the reproduction of the environment that the project was conducted in first. Only then can the analysis be replicated succesfully.  

#### 1.) Recreate the environment that the analysis was conducted in ####

The project files that i present offer two ways to do this for to account for the two most popular package managers for python. Let's start with the preferred method first:

##### a.) Using the environment.yml file with conda package manager #####

You can use this option if you have the conda package manager installed in your computer. The preferred method is to cd to the directory of the project and then run the following command in the Anaconda prompt (or any terminal where you can run conda from):

<conda env create -f environment.yml>

Running this command will make conda create a new environment similar to the environment of the analysis with the information provided inside the environment.yml file. When you run the command, you will be able to specify the name of this new environment. Once you are done, **don't forget to activate your environment before running the analysis.**


#### b.) Create the environment yourself and load the packages using the requirements.txt and pip ####

It is still possible to recreate the original environment if you are not using the conda package manager. The pip manager that comes with many Python installers is able to install requirements using the requirements.txt file present in the project. **However, you first need to create an environment yourself seperate from you base Python environment so as to prevent potential problems** The process of creating a virtual environment through pip is lengthier than the method above. [Here's the official documentation of how to install packages and create virtual environments using pip.](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

Once you have created your environment, you can now install all the packages using the requirements.txt file. To do so, **activate your virtual environment**, cd to the project folder and run the following in a Python terminal:

<pip install --requirement requirements.txt>

#### 2.) Second Way ####

##### Do This #####

##### Do That #####

## Project  Organization ##

Below is a document tree of this project for those who wish to explore further.

--------
    ├── LICENSE            < - License for the codes responsible in creating this data analysis projects.
    |
    |
    |
    ├── README.md          <- The top-level README for developers using this project.
    |
    |
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling and visualization.
    │   └── raw            <- The original, immutable data dump.
    │
    │
    ├── eda_notebooks      <- Jupyter notebooks that have data explorations. These files were not created with external viewers in mind.
    |                         You can explore them if you wish. However, a good viewing experience is not promised.
    |
    |
    |── media              <- Contains internally generated figures and external photos. Internally generated figures come with a license.
        ├── external_media       <- Images and media downloaded from third party resources. A .txt file of references and attribution is included.
    │   ├── figures        <- Data visualizations generated through scripts
    |                                             
    |
    |
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │
    |
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    |
    |
    |── environment.yml    <- A .yml file for reproducing the analysis environment. For a recreation guide, see **how to reproduce this project.** above.
    |
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    |
    |
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data_preparation        <- Scripts to download or generate data
    │   │   └── prepare_data.py     <- Final script to run all cleaning and prepration subscripts.
    |   |
    |   |── data_analysis           <- Scripts to generate intermediary datasets to base visualizations on.                           
    |   |   └──analyze_data.py      <- Final script to run all analysis subscripts.
    │   │
    │   └── visualization           <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize_data.py   <- Final script to run all visualization subscripts.
--------

* * *

## References ##

<p>
    <small>The Cookiecutter template of this project is based on a version of the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">DrivenData Cookiecutter Data Science project template.</a></small>
</p>

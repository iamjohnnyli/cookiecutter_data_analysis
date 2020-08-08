# Cookiecutter Data Analysis Template

This is a [cookiecutter template](http://drivendata.github.io/cookiecutter-data-science/) for data analysis. This template will jump start your data science projects.

#### Quick Start

- Install Cookiecutter Python package

    ```shell
    pip install cookiecutter
    ```
    or
    ```shell
    conda config --add channels conda-forge
    conda install cookiecutter
    ```
- Run Cookiecutter
    ```shell
    cookiecutter https://https://github.com/iamjohnnyli/cookiecutter_data_analysis
    ```

#### Folder Structure
The directory structure of your new project looks like following:

    ├── LICENSE
    ├── README.md          
    |── 01_Data_Prep.ipynb <- Notebook for prepare Data for analysis
    |── 02_Analyze.ipynb   <- Notebook for analysis
    ├── data               
    ├── reports            <- Analysis reports
    ├── requirements.txt   
    └── src                <- scripts used in this project
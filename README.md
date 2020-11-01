# **CS5615 - Information Retrieval - Assignment 1 - Basic Text Preprocessing Techniques**
### **Author - KATS JAYATHILAKA (209338R)**
This repository is used to develop an implementation of basic text pre-processing techniques using available software tools for an assignment for the module of Information Retrieval in MSc in Data Science, Analytics and Engineering, University of Moratuwa.

## 

## **Instructions to run the code**

### <ins>1. Creating separate anaconda environment</ins>

It is better to have a separate conda environment with python3. Follow the instructions to run the code.
1. [Install Anaconda](https://www.anaconda.com/products/individual)   
2. Make sure conda is automatically added to
    - Environment variables in Windows OR
    - System path in Linux (Ubuntu)
3. Anaconda will come with a base environment with preinstalled Python3.8. You can that default base environment by activating it as follows.
    - `conda activate`
4. Or else, you can create your own separate anaconda environment with just for testing this assignment and delete that environment later.
    - `conda create -n yourenvname python=x.x anaconda`
5. To activate/deactivate your conda environment.
    - `conda activate yourenvname`
    - `conda deactivate`
6. ADDITIONAL STEP: To make sure Jupyter notebook and Ipykernel are installed in your conda environment.
    1. Check whether Jupyter notebok and Ipykernel 
        - `conda list | grep jupyter`
        - `conda list | grep ipykernel`
    2. If the above commands doesn't output anything to the terminal, install the packages as follows.
        - `conda install -c conda-forge notebook`
        - `conda install -c anaconda ipykernel`
7. Add your conda environment to jupyter notebook as a specific kernel as follows.
    - `python -m ipykernel install --user --name=yourenvname`
8. Open jupyter notebook by the following command and then open the assignment notebook and run the tests.
    - `jupyter notebook`
9. You can delete the conda environment you created to evaluate this assignment by the following command.
    - `conda remove -n yourenvname -all`

### <ins>2. Preprocessing 'assignment_data.txt'</ins>

1. Clone the following git repo into your machine.
   - `https://github.com/tsj1992/CS5615-IR-A1-Basic-Text-Preprocessing-Techniques.git`
2. Olarika

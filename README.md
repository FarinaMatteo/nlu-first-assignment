# nlu-first-assignment
Repository containing the material for the 1st Assignment of the Natural Language Understanding course at University of Trento - MSc in Artificial Intelligence Systems.

## Repository Structure  
The content of the repository is organized as shown in the snippet below.
```
nlu-first-assignment
|── data/
    |── mandatory/
        |── examples.txt (sentences used for demonstrative purposes)
    
|── mandatory.ipynb (notebook containing the mandatory tasks of the  assignment)
|── README.md (this file)
|── LICENSE 
|── .gitignore
```  
Since I've made use of Jupyter Notebooks, there is no external report. Instead, every code cell in the .ipynb files is preceded by a Mardown cell that briefly describes the implemented logic and, thus, plays the role of the report.  
  
  
## Requirements and Dependencies  
Each notebook contains an introductory section named *requirements*, where the tasks needed in order to have your system up und running are listed. However, those steps are also shortly reported down below. Both notebooks run under the Python v3.9 interpreter. Before opening the notebooks, run:  
```
$ pip install jupyter
```

1. ## Mandatory
Run the commands below to install what's needed for **mandatory.ipynb**.
```
$ pip install spacy
$ python -m spacy download en_core_web_sm
```


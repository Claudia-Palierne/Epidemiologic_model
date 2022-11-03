# Epidemiologic Model

## Configuration

This project is a Jupyter Notebook. The required libraries can be downoload here :
```
pip install -r requirement.txt  
```

## Description

Previously to the actual Corona virus SARS Cov-2 crisis, several epidemics occurred in history. Already in Antiquity, due to the lack of treatment and knowledge, diseases have decimated entire populations in few months or even few weeks. Nowadays, a scientific discipline named epidemiology study method to find the causes of health outcomes and diseases in populations.  

Several model has been developped nowadays to understand the spread of an epidemy. I choosed to illustrate several models (from the simplest one to the most complex) :  

1. SIR, where people can be Infected (I), Recovered (R) or Susceptible (S, i.e. people that can get sick).
2. SEIRS, where people can get susceptible again after they got sick and where people have a period of incubation (E).
3. A model with solution including vaccination and quarantine.

**All the models are based on ODE's and allows the you to play with all the hyperparameter.**

## Run the code

To run the code and get more details on each model :
```
jupyter model.ipynb
```
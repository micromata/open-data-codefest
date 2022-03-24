# Codefest
AVAPS - Vorhersage des Gewichts von Spritzgußteilen (Teilequalität).
## Setup conda environment:
Leider nur getestet auf einem MAC Book Pro. Bei anderen Betriebssystemen könnte es anders aussehen.
1. Install miniconda (https://docs.conda.io/en/latest/miniconda.html)
2. Create conda environment: ```conda create -n codefest_env python==3.9.5``` 
3. Activate Conda environment: ```conda activate codefest_env```
4. Install packages of the requirements.txt, with ```conda install <package>```
5. register kernel for jupyter notebook: ```python -m ipykernel install --name codefest_env --user```
6. Start juypter lab : ```jupyter-lab```

# Example
./src/example.ipynb : enthält ein beispielhaftes Vorgehen, um die Daten zu analysieren und eine Lineare Regression zur Vorhersage des Teilegewichts durchzuführen. 

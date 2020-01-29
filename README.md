# Modeling wolf population in the Netherlands
### Project description
This Github repository contains code that can be used to simulate and visualise the effects of several factors and events in an ecosystem with a single predator and two types of prey. 

This repository contains two jupyter notebooks:

    1. Lotka-Volterra test.ipynb
    2. Previous version (1 predator 1 prey model).ipynb

The first notebook contains the most recent code. The second notebook is an older implementation containing a model with only a single predator and a single prey.

### Dependencies
To run the code you need jupyter notebook. To install this for Python 3, run the command:
    ```
    pip3 install jupyter
    ```

For more information on how to install Jupyter Notebook, refer to:
https://jupyter.org/

The following modules are used in the code:
    - numpy
    - matplotlib.pyplot
    - scipy
    
If youuse an Anaconda Distribution all these modules are already installed. If not you can use the following command to install them:
```python -m pip install --user numpy scipy matplotlib```

For more information on how to install these modules, refer to:
https://www.scipy.org/install.html

### How to reproduce the graphs?
Run the command: ```jupyter notebook``` in your terminal to open jupyter notebook.

Once jupyter notebook is running open the file Lotka-Volterra test.ipynb in the
notebook.

Run all the cells by going to kernel -> restart & run all.

To start the simulation press the button Run interact.
Use the sliders to change the parameters.

The final graphs are at the end of the file under the header Model validation.

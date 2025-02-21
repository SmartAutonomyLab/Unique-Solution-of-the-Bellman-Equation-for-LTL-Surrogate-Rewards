The repo builds on CSRL project (in this [article](https://arxiv.org/abs/1909.07299).) of Duke University and apply Q-Learning, Model-Checking, Value Iteration to the grid world case study.
## Dependencies
 - [Python](https://www.python.org/): (>=3.5)
 - [Rabinizer 4](https://www7.in.tum.de/~kretinsk/rabinizer4.html): ```ltl2ldba``` must be in ```PATH``` (```ltl2ldra``` is optional)
 - [NumPy](https://numpy.org/): (>=1.15)
 - [scipy](https://scipy.org/)
 - [dill](https://pypi.org/project/dill/)

The examples in this repository also require the following optional libraries for visualization:
 - [Matplotlib](https://matplotlib.org/): (>=3.03)
 - [JupyterLab](https://jupyter.org/): (>=1.0)
 - [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/): (>=7.5)
 - [tqdm](https://github.com/tqdm/tqdm)


Case_study_Prodcut_MDP.ipynb uses drill to store the product MDP model into workspace product_MDP.pkl. 
Case_study_2025_Nursery Scenario.ipynb use drill to load the workspace file product_MDP.pkl, then apply Q-Learning, Model-Checking, Value Iteration. 

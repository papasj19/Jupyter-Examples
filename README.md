# A collection of completed Jupyter Notebooks

by Spencer Johnson
on February-June 2023

## Utilities Consulted

* [Jupyter](https://jupyter.org)
* Libraries:
	* [Pandas](https://pandas.pydata.org) 
	* [Seaborn](https://seaborn.pydata.org)
	* [Matplotlib.pyplot](https://matplotlib.org)
	* [sklearn](https://scikit-learn.org/stable/)
	* [NumPy](https://numpy.org)

## Contents

* Descriptive Analytics:
    * `studentAnalysis.ipynb`
    * education.csv (dataset)

* Predictive Analytics:
    * `clientAnalysis.ipynb`
    * heart.csv (dataset)

* Search Algorithms:
    * `Blind_Search.ipynb`
    * mazes (a folder containing datasets of increasing sizes)
        * maze1.txt (smallest)
        * maze2.txt
        * maze3.txt (biggest dataset)

## Change datasets

The dataset that is provided and used for the Descriptive Analytics section is extremely large. It is data regarding students at a school and their grades. There is four years and around 70,000 students per year. There is not another dataset. 

The data set for Predictive Analytics is not as large as the one mentioned above. There does not exist another dataset for this section either. 

To swap between the different datasets for the Search Alorithms section, just edit the line from `Blind_Search.ipynb` shown below and change the name of the txt file to one of larger size that you want to use.
```python
m = Maze("/content/maze2.txt") 
```

## Contact

Spencer Johnson - spencerjames.johnson@students.salle.url.edu - [@papasj19](https://www.instagram.com/papasj19/)

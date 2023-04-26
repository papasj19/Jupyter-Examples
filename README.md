# A collection of Jupyter Notebooks completed in my Knowledge Based Systems Classes

by Spencer Johnson
on February-June 2023

## S

* [Jupyter](https://jupyter.org)
* Libraries:
	* [Pandas](https://pandas.pydata.org) 
	* json
	* datetime
	* math
	* calendar

## How to execute the code

If you are using Visual Studio Code with the Python Extension installed, you 

```bash
$ python code/read_json.py
```

## Change datasets

To swap between the different datasets, just edit line 183 from `read_json.py` and change the name of the file to the one from the actual file you want to use. Make sure you also write the correct route to that file.
```python
with open('<file_route>/<file_name>.json','r',encoding="utf8") as f:
```

We checked the code for all three datasets (S, M, L) and it worked properly.

## Contact

Spencer Johnson - spencerjames.johnson@students.salle.url.edu - [@papasj19](https://www.instagram.com/papasj19/)

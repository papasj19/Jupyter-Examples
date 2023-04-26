# Project 1 - LSManga

by Spencer Johnson & Oriol Segura i Niño
on Sunday 28th November 2021

The following explanation is in conjunction with PAED Project 1

## System requirements

* [Python 2.7](https://www.python.org/downloads/) or later
* Python libraries:
	* os 
	* json
	* datetime
	* math
	* calendar

It was tested using the Python Extension v2021.11 from [Visual Studio Code 1.62.3](https://code.visualstudio.com/download)

## How to execute the code

If you are using Visual Studio Code with the Python Extension installed, you can simply click the green arrow from the top right corner to run it on the VSC terminal once the file is opened.

Otherwise, open the terminal and head to the folder where the project is located and run:

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

Spencer Johnson - spencerjames.johnson@students.salle.url.edu - [@papasj19](https://www.instagram.com/papasj19/) - Nintendo Friend Code: SW-7216-7178-5216

Oriol Segura - oriol.segura@salle.url.edu - [@0rikik0](https://www.instagram.com/0rikik0/) - [オリキコ君#2728](https://discordapp.com/users/376777722686341121)

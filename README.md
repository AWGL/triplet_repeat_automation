# Triplet_repeats

## Requirements:

* numpy
* pandas
* xlrd
* pyinstaller 


## Download the directory:

```
git clone https://github.com/LauraMcCluskey7/Triplet_repeats.git 

```


## Run from the command line:

```
python triplet_repeat_automation.py <gene> <worksheet_number>
```


## Create the executable:


The executable file must be created on a windows platform

```
pip install pyinstaller
```

```
pyinstaller get_triplet_repeats-3_alleles.py

```


## Run the executable:


* Click on the executable 
* Input the gene name and worksheet number into the console



## Run tests in the project root directory


```

python -m unittest discover

```

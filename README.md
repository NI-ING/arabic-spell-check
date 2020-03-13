# arabic-spell-check

Spell check for Arabic text using python 

## Installation 
For hunspell, you need to install the following packages 
```
sudo apt install hunspell-ar
sudo apt install libhunspell-dev
sudo apt install aspell
sudo apt install libaspell-dev
sudo apt install aspell-ar
sudo apt install aspell-ar-large
pip install hunspell
pip install aspell-python-py3
```
## Usage hunspell 
```hunspell-check.py [-h] -i INFILE -o OUTFILE```

Arabic spell checker based on hunspell. The input is a file and the output is errors with
frequencies and suggestion. 

## Usage aspell 
```aspell-check.py [-h] -i INFILE -o OUTFILE```

Arabic spell checker based on aspell. The input is a file and the output is errors with
frequencies and suggestion. 

## Arguments:
  -h, --help            show this help message and exit
  
  -i INFILE, --infile INFILE (input file).
                        
  -o OUTFILE, --outfile OUTFILE (output file).



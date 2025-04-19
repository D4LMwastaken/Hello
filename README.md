# Hello

A stupidly simple program that should not win "Terminal" Hackathon

## Project structure:
```
├── .ropeproject # Project config folder for Zed, has nothing, go find out why...
├── .venv # Unnecessary but a virtual enviroment nevertheless.
├── .env # Should not be here, who cares, go look inside!
├── main.py # The main file!
├── LICENSE.md # Stops people from just copying without including the license
├── README.md # The file you are reading right now!
└── requirements.txt # Should have dependencies but for Python specific libraries...
```

## How to install:

### Dependencies:
* Linux (Sorry no Windows... might do it as well)
* Python3 (Check below(maybe just python?))   
```bash
python3 --version
```
If not, go follow instructions [here!](https://www.geeksforgeeks.org/how-to-install-python-on-linux/)

### Steps to install (User, no need for system):
Copy this into your terminal:
```bash
curl -o hello https://raw.githubusercontent.com/D4LMwastaken/Hello/main/main.py && chmod +x hello && mv hello ~/.local/bin/ && exec bash
```

### Steps to remove:
Copy this into your terminal:
```bash
rm ~/.local/bin/hello && exec bash
```

## Steps to run:
```bash
hello
```
# Project 3: Piece of Cake
## Summary

Course: COMS 4444 Programming and Problem Solving (Fall 2024)  
Problem Description: https://www.cs.columbia.edu/~kar/4444f24/node20.html  
Course Website: https://www.cs.columbia.edu/~kar/4444f24/4444f24.html
University: Columbia University  
Instructor: Prof. Kenneth Ross 
TA Designer for this project: Divyang Mittal
Project Language: Python

## Group 6
View the complete report [here](https://drive.google.com/file/d/1w9aI48wtcBFW02b6cJQv_06UDr_EBkUO/view?usp=sharing)
Fastest and most efficient!
Grid cutting algorithm
Team: Adithi Narayan, Aditya Nangia, Divyang Mittal

## Installation

Requires **python3.10** or higher

```bash
pip install -r requirements.txt
```

To install tkinter on macOS, run the following command:
```bash
brew install python-tk@3.X
```

Setup miniball library
```bash
git clone https://github.com/hbf/miniball
cd miniball/python
pip install .
```

## Usage

To view all options use python3 main.py -h
```bash
python3 main.py [-d/--tolerance] [-rq/--requests] [-s/--seed]  [-sc/--scale] [-ng/--no_gui] [-p/--player]
```

To try our implementation run with --player 6 or -p 6
```bash
python3 main.py -d 15 -rq "requests/default/easy.json" -p 6
```

## Debugging

The code generates a `log/debug.log` (detailed), `log/results.log` (minimal) and `log\<player_name>.log` 
(logs from player) on every execution, detailing all the turns and steps in the game.

## Example Usage
```bash
python3 main.py -d 15 -rq "requests/default/easy.json"
```

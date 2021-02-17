# bskull-openings

Dominion is a game where a small advantage early in the game can snowball into a decisive advantage later on. As such, the opening (i.e your buys in the first two turns of the game) is very important in laying the foundation for your strategy throughout the rest of the game.

This repository contains manually collected data about openings from [How to Base Dominion](https://www.youtube.com/watch?v=JpPtxyGNGcg&list=PLtkTUMIr-WmKZCd4Q_KnrKtNJKR-vpC8a), a YouTube series by Burning Skull, one of the best dominion players in the world. This data is processed, analyzed, and visualized in Jupyter Notebook using the Pandas, TrueSkill, and Matplotlib libraries in Python. The end result is rankings of the openings in this dataset from best to worst.

## Usage
You can simply view in your browser: [How To Base Dominion Opening](https://github.com/zuirod/bskull-openings/blob/main/How%20to%20Base%20Dominion%20Opening.ipynb).

For those who would like to dig through the code, install the requirements below, then run the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):

```jupyter notebook```

A browser window should open. Wait for the page to load, then click 'How to Base Dominion Opening.ipynb'. Click Kernel > Restart & Run All to run all the cells, or Shift + Enter to run an individual cell.

## Requirements

Run the appropriate commands at the Terminal (Mac/Linux) or Command Prompt (Windows).

### Install with conda

If you have [Anaconda or Miniconda](https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/index.html) installed, run:

Create a conda environment:

```conda create --name bskull-openings --file requirements.txt```

Activate the environment:

```conda activate bskull-openings```

### Install with pip

Alternatively, if you have [Python](https://www.python.org/downloads/) installed, run:

```pip install notebook pandas matplotlib trueskill lxml```

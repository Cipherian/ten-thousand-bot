# Ten Thousand Game

## Project: Lab: 09 - Guided Project IV

### Authors: Natalija Germek, Daniel Brott, Andy Nguyen

## Links and Resources

Consulted these resources on how to optimize points:
1. http://www.mattbusche.org/blog/article/optimal_farkle/
2. http://www.mattbusche.org/downloads/farkle/optimal-play-farkle.pdf

## Notes

All code was pulled from class repo and left as is. The only code added was the code for the group's bot.

## Version 1

- GameLogic class
  - roll_dice
  - calculate_score

- Banker
  - deposit/bank
  - shelf
  - clear

## Version 2

- beginning Game class
  - allows banking or quitting on first roll of multiple rounds
  - no rerolls
  - no zilches
  - no cheating checks
- Introducing Flow testing with Flo

## Version 3

- validate_keepers
- get_scorers
- Advanced Game class
  - rerolls allowed
  - using all six dice resets to six dice
  - zilches happen
  - cheating is checked

## Version 4

- Bot time

## Setup

Make sure you are in the repo's root directory first and that you have python 3.10 installed.

Create a `venv` environment:

```bash
python3 -m venv .venv
```

Activate `venv` environment:

```bash
source .venv/bin/activate
```

Install dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

Run the bots:
```bash
python bots.py
```

Deactivate `venv` environment:

```bash
deactivate
```

### How to run all the tests in the repository

Make sure you are in the repo's root directory first.

```bash
pytest -v
```
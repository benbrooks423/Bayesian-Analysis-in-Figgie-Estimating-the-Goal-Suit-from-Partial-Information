# Bayesian-Analysis-in-Figgie-Estimating-the-Goal-Suit-from-Partial-Information



## Overview
This program calculates probabilities and expected values in the card game Figgie. It utilizes the hypergeometric distribution to estimate suit compositions and determine optimal strategies for trading cards.

## Features
Computes posterior probabilities of suit sizes using Bayes' theorem.
Estimates the likelihood of holding the most cards in a suit.
Evaluates the expected value of purchasing a card.
Provides an interactive input system for entering hand and revealed card data.

## Installation
### Requirements
Python 3.x
scipy library (for statistical calculations)

### Setup
Clone or download this repository.
Install dependencies with:
pip install scipy
Run the script:
python figgie_probability.py

## Usage
Enter the number of each suit in your 10-card hand.
Optionally, enter revealed cards.
The program will compute probabilities and suggest strategic moves.
View the expected value of buying a card for each suit.

## Mathematical Background
This program applies the hypergeometric probability distribution to model suit sizes. It uses Bayes' theorem to update beliefs about suit compositions based on observed cards.

# Greedy_algorithm

This simple C program calculates the minimum number of coins needed to provide change for a given amount in cents. It is designed as part of the CS50 course.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)
- [Functions](#functions)
- [How to Contribute](#how-to-contribute)
- [License](#license)

## Overview

This program prompts the user to input the amount of change owed in cents and then calculates the optimal distribution of quarters, dimes, nickels, and pennies to make up that change. The total number of coins needed is then printed.

### Individual Functions

1. **get_cents():**
   - Prompts the user to input the amount of change owed in cents using `get_int` from the CS50 library.

2. **Coin Calculation Functions:**
   - `calculate_quarters(cents)`
   - `calculate_dimes(cents)`
   - `calculate_nickels(cents)`
   - `calculate_pennies(cents)`
   - Each function takes the remaining cents as input and calculates the number of respective coins needed (quarters, dimes, nickels, or pennies) by dividing the remaining cents by the value of the coin.

## Usage

1. Clone the repository to your local machine.
   ```bash
   git clone <repository-url>


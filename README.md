# Greedy_algorithm

This C program calculates the minimum number of coins needed to provide change for a given amount in cents.

## Overview

This program is a simple change calculator that helps determine the optimal distribution of quarters, dimes, nickels, and pennies for a specified amount of change in cents.

### How It Works

1. **User Input:**
   - The program starts by prompting the user to input the amount of change owed in cents using the `get_cents` function.

2. **Coin Calculation:**
   - It then calculates the number of quarters, dimes, nickels, and pennies using separate functions (`calculate_quarters`, `calculate_dimes`, `calculate_nickels`, `calculate_pennies`). Each function calculates the number of coins of a specific denomination based on the remaining cents.

3. **Output:**
   - The total number of coins needed is then printed, providing the minimum number of coins required to make up the given change.

### Functions

#### `get_cents()`

Prompts the user to input the amount of change owed in cents using `get_int` from the CS50 library.

#### `calculate_quarters(int cents)`

Calculates the number of quarters needed based on the remaining cents.

#### `calculate_dimes(int cents)`

Calculates the number of dimes needed based on the remaining cents.

#### `calculate_nickels(int cents)`

Calculates the number of nickels needed based on the remaining cents.

#### `calculate_pennies(int cents)`

Calculates the number of pennies needed based on the remaining cents.

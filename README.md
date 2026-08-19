# Invoice Generator

A Python command-line application that generates invoices from user-provided
customer and product information.

The project focuses on input validation, calculation logic, discount handling,
and formatted invoice output.

## Features

- Collects customer information
- Adds multiple products to an invoice
- Records product price and quantity
- Calculates individual item totals
- Calculates the invoice subtotal
- Supports percentage-based discounts
- Validates user input
- Handles invalid numeric input
- Generates a formatted command-line invoice

## Technologies

- Python 3
- Python standard library

## How It Works

The application follows a simple workflow:

1. The user enters their name.
2. The user adds one or more products.
3. Each product is given a price and quantity.
4. The application calculates the total for each item.
5. The application calculates the invoice subtotal.
6. The user can optionally apply a discount.
7. The final invoice is displayed in the terminal.

## Input Validation

The application validates several types of user input.

### Product

Product names cannot be empty.

### Price

Prices must be valid numbers. The application also accepts prices entered
with a `£` symbol.

### Quantity

Quantities must be whole numbers greater than zero.

### Discount

Discounts must be between 0% and 100%.

The application also accepts percentage values such as:

```text
10%

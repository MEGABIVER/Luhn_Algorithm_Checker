# Luhn Algorithm Card Validator

This is a simple Python program that verifies whether a credit or debit card number is valid using the [Luhn algorithm](https://en.wikipedia.org/wiki/Luhn_algorithm).

## 🔍 How It Works

The Luhn algorithm follows three main steps:

1. Starting from the right, double every second digit.
2. If doubling a digit results in a number greater than 9, subtract 9 from it (or sum the two digits).
3. Sum all the digits. If the total is divisible by 10, the card number is considered **valid**.

## 📦 Example

```python
card_number = '4111-1111-4555-1142'

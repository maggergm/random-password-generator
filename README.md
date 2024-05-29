# Random Password Generator

A simple Python library for generating random passwords.

## Features
- Generate passwords of custom length.
- Include digits and special characters optionally.
- Evaluate password strength.
- Generate mnemonic passwords for easy memorization.
- Easy to use.

## Installation
No installation required. Just download the `passwordgen` and `password_strength` files and include them in your project.

## Usage

```python
from passwordgen import PasswordGenerator
from password_strength import evaluate_password_strength

# Generate passwords
print(PasswordGenerator.generate_password())
print(PasswordGenerator.generate_password(length=16, use_digits=False))
print(PasswordGenerator.generate_password(length=8, use_special_chars=False))

# Evaluate password strength
print(evaluate_password_strength("weakpass"))
print(evaluate_password_strength("Str0ngP@ssw0rd!"))

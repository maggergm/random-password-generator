# Random Password Generator

A simple Python library for generating random passwords.

## Features
- Generate passwords of custom length.
- Include digits and special characters optionally.
- Easy to use.

## Installation
No installation required. Just download the `passwordgen` file and include it in your project.

## Usage

```python
from passwordgen import PasswordGenerator

print(PasswordGenerator.generate_password())
print(PasswordGenerator.generate_password(length=16, use_digits=False))
print(PasswordGenerator.generate_password(length=8, use_special_chars=False))

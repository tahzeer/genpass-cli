# GenPass CLI

[![Build Status](https://github.com/tahzeer/genpass-cli/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/tahzeer/genpass-cli/actions/workflows/test.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/tahzeer/genpass-cli/branch/main/graph/badge.svg)](https://codecov.io/gh/tahzeer/genpass-cli)


A simple yet powerful command-line password generator.

## Features

- Generate secure passwords with customizable options
- Copy passwords directly to clipboard
- Specify password length
- Include/exclude special characters, numbers, and uppercase letters
- Quiet mode for scripting

## Installation

```bash
pip install genpass-cli
```

## Usage

Basic usage:
```bash
genpass

# Generate a longer password
genpass -l 16

# Generate password without special characters
genpass --no-special

# Generate and copy to clipboard
genpass -c

# Quiet mode (only output password)
genpass -q
```

## Examples

```bash
# Generate a 20-character password with all character types
genpass -l 20

# Generate a simple password (only letters and numbers)
genpass --no-special

# Generate and copy to clipboard silently
genpass -q -c
```

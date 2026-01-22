
# StackLib

A chainable, stack-based utility library for Python.

## Installation

```bash
pip install StackLib
```
## Basic usage

```python
from stacklib.Stack import stack

stack = stack()
stack.push(10).push(5).add()

print(f'stack: {stack}')
```
## Features

- Chainable stack operations
- Functional helpers (map, filter, apply-at)
- Logical operations (sand, sor, snot)
- Stack manipulation (dup, swap, rot, over)
- Snapshots and restore

## Why it exists
Inspired by stack-based languages (Forth, PostScript) and because i thought it was a fun project.

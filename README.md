# Week 6 Assignment: Safe Functions

## Files
- `safe_tools.py` - Contains three safe functions for division, number conversion, and dictionary lookup.
- `README.md` - Explains the assignment and the purpose of each file.

## Reflection
An if check cannot catch `abc` on its own because `abc` is valid text but cannot be converted into a whole number using `int()`. Python raises a ValueError during conversion, so try/except is used to handle the error safely.

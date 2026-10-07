
# Safe Tools Assignment

## Files:
- `safe_tools.py`: Contains three safe functions for division, number conversion, and dictionary lookup.

## Why can't the if check catch "abc" on its own?
The `if` check can't catch "abc" because Python is dynamically typed
and doesn't know if a string like "abc" should be treated as a number or not until it tries to convert it.
The `try-except` block catches the explicit error (`ValueError`) raised when attempting the conversion with `int()`.

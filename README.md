# ezargs
Lightweight, zero-setup dynamic Python command line argument parsing

## Usage:
1. When invoking your Python script, pass key-value pairs in the format `key=value`.
    * eg. `python my_scripy.py duration=5 max_shift=12 name=foo`
3. In your code, just be sure to call `args: dict = parse_args()` before you need to access the arguments in your program.

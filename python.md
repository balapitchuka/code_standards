# Python Coding Style)

References
+ [PEP-8 official documentation](https://www.python.org/dev/peps/pep-0008/)
+ [Python Code Quality](https://testdriven.io/blog/python-code-quality/)
+ [Python Type Checking](https://testdriven.io/blog/python-type-checking/)
+ [Documenting Python Code and Projects](https://testdriven.io/blog/documenting-python/)



### PEP 8 (Python Enhancement Proposal)
PEP 8 is a style guide that describes the coding standards for Python. It's the most popular guide within the Python community.
  
PEP 8 naming conventions:
  + class names -  CamelCase (MyClass)
  + variable names - snake_case and all lowercase (first_name)
  + function names - snake_case and all lowercase (quick_sort())
  + constants - snake_case and all uppercase (PI = 3.14159)
  + modules should have short, snake_case names and all lowercase (numpy)
  + single quotes and double quotes are treated the same (just pick one and be consistent)

PEP 8 line formatting:
  + indent using 4 spaces (spaces are preferred over tabs)
  + lines should not be longer than 79 characters
  + avoid multiple statements on the same line
  + top-level function and class definitions are surrounded with two blank lines
  + method definitions inside a class are surrounded by a single blank line
  + imports should be on separate lines


PEP 8 whitespace:
  + avoid extra spaces within brackets or braces
  + avoid trailing whitespace anywhere
  + always surround binary operators with a single space on either side
  + if operators with different priorities are used, consider adding whitespace around the operators with the lowest priority
  + don't use spaces around the = sign when used to indicate a keyword argument

PEP 8 comments:
  + comments should not contradict the code
  + comments should be complete sentences
  + comments should have a space after the # sign with the first word capitalized
  + multi-line comments used in functions (docstrings) should have a short single-line description followed by more text

    

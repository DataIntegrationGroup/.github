## Do's
1. use `with` to open files
   ```python

   with open(path_to_file, 'r') as rfile:
     ...
   ```

2. use list comprehension when possible
3. use dict comprehension when possible
4. use generators
   ```python
   f = next((x for x in xs if predicate), None)
   ```
5. private methods should start with `_`
   ```python
   class A:
     def _add(self, a):
       ...
   ```
   

## Dont's
1. don't use `import numpy as np` or `import pandas as pd`, etc.
   ```python
   from numpy import linspace, mean
   from pandas import Dataframe
   ```

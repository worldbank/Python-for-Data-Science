# Writing clean code based on PEP8 guidelines

### Clear and well-written code is important. The main set of conventions for Python, written by Guido Van Rossum, is called [PEP8](https://www.python.org/dev/peps/pep-0008/#prescriptive-naming-conventions).

### For our course, remember the following:

### 1. Maximum line length

Lines of code shouldn't exceed 79 characters.
To comply with this, break code into several lines by wrapping expressions in parentheses.

### 2. Imports

Import libraries at the top of your notebook. Use a new line for each import.
Learn the conventional shortened names for common libraries (eg. import pandas as pd).

__YES:__

```
import sys

import os

```
__NO__: 

```
import sys, os

```

### 3. Declaring strings

Python lets you use single quotes or double quotes around strings; pick one option and stick to it.

__YES:__

```
string1 = 'I love Python'

string2 = 'not R'
```

__NO__:
```
string1 = "I love Python"

string2 = 'not R'
```

### 4. Whitespace

Use spaces between operators

Be consistent and don't add redundant whitespace.

__YES:__

```
a = b + c

spam(ham[1], {eggs: 2})

```
__NO__:

```
a=b+c

spam( ham[ 1 ], { eggs: 2 } )
```

### 5. Comments

Start comments with # and a single space.

__YES:__
```
x = x + 1          # Increment x
```

#### 6. Naming

Function and variable names should be lowercase, with underscores between the words as necessary to improve readability.

Use descriptive variable names.

__YES:__

```
mean_trip_time = []
```

PROBABLY NOT:
```
mtt = []
```

# Hyperion_obf [![Downloads](https://pepy.tech/badge/Hyperion_obf)](https://pypi.org/project/Hyperion_obf/)

## Langage

Python 3.9.4

## Install

```sh
pip install hyperion_obf
```

## How To Use

This module contains only one function called obfuscate that returns the code obfuscated

```python
import Hyperion_obf

#Obfuscate code from string
print(Hyperion_obf.obfuscate(script="print('Hello, world!')"))
#Obfuscate code from a file
print(Hyperion_obf.obfuscate(file="code.py"))
```

## Parameters

The function obfuscate have 4 parameters:

file: The name of the file you want to be obfuscated.
script: The script to obfuscate.
skiprenaming: If true all the variables won't be renamed
skipchunks: If true the script will skip the protection of chunks

# Credits

Hyperion is made by Billythegoat356 & Bluered

I just made a module , all the merit is theirs

https://obf.plague.fun/obf/

https://github.com/billythegoat356/Hyperion

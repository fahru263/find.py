<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/find.svg?longCache=True)](https://pypi.org/project/find/)
[![](https://img.shields.io/pypi/v/find.svg?maxAge=3600)](https://pypi.org/project/find/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/find.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/find.py/)

#### Installation
```bash
$ [sudo] pip install find
```

#### Functions
function|`__doc__`
-|-
`find.dirs(path, followlinks=False)` |return a list of dirs
`find.files(path, followlinks=False)` |return a list of files

#### Examples
```python
>>> import find

>>> find.files(".")
['path/to/requirements.txt','path/to/setup.py','path/to/package/__init_.py',...]

>>> find.dirs(".")
['path/to/package','path/to/tests',...]
```

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>
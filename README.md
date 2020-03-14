# pythons-language-tools-list
Supported list of Python Packages and articles that allows you to work with language on different levels - tokens, CST, AST and etc

TODO: need clean up list and structure

https://github.com/davidhalter/jedi
Jedi - an awesome autocompletion/static analysis library for Python

https://jedi.readthedocs.io/en/latest/

Features: 
	autocompletion 
	getting types based on docstrings (4 types) and type annotations 


Parso is a Python parser that supports error recovery and round-trip parsing for different Python versions (in multiple Python versions). Parso is also able to list multiple syntax errors in your python file.
Parso has been battle-tested by jedi. It was pulled out of jedi to be useful for other projects as well.


Was part of Jedi, separated in package
https://github.com/davidhalter/parso 
https://parso.readthedocs.io/en/latest/ 

Features:

	Parso consists of a small API to parse Python and analyse the syntax tree.


Language services:

https://github.com/palantir/python-language-server (use Jedi inside, so if you want some usage samples - welcome)



Rope
https://github.com/python-rope/rope/blob/master/docs/library.rst#quick-start 
https://github.com/python-rope/rope 
python refactoring library ...
 

Samples of how to work with language tools: 
https://github.com/PyCQA/pyflakes/blob/master/pyflakes/checker.py 
https://github.com/PyCQA/mccabe/blob/master/mccabe.py 
Linters:


Tool	Category	Description
Mccabe	Analytical	Checks McCabe complexity
Radon	Analytical	Analyzes code for various metrics (lines of code, complexity, and so on)
Black	Formatter	Formats Python code without compromise
Isort	Formatter	Formats imports by sorting alphabetically and separating into sections
Pylint	Logical & Stylistic	Checks for errors, tries to enforce a coding standard, looks for code smells
PyFlakes	Logical	Analyzes programs and detects various errors
pycodestyle	Stylistic	Checks against some of the style conventions in PEP 8
pydocstyle	Stylistic	Checks compliance with Python docstring conventions
Bandit	Logical	Analyzes code to find common security issues
MyPy	Logical	Checks for optionally-enforced static types

https://github.com/timothycrosley/isort
https://github.com/timothycrosley/isort/blob/develop/pyproject.toml 

https://github.com/psf/black/blob/master/black.py

App dirs 
https://pypi.org/project/appdirs/ 

https://radon.readthedocs.io/en/latest/
Radon is a Python tool which computes various code metrics. Supported metrics are:
* raw metrics: SLOC, comment lines, blank lines, &c.
* Cyclomatic Complexity (i.e. McCabe’s Complexity)
* Halstead metrics (all of them)
* the Maintainability Index (a Visual Studio metric)
Radon can be used either from the command line or programm
 

https://pivotfinland.com/pytest-sugar/


Bytecode 

https://pypi.org/project/xdis/ 

https://github.com/rocky/python-xasm


Parsers language 

An Earley Algorithm Parser toolkit.

https://github.com/rocky/python-spark/tree/master/example

https://pypi.org/project/uncompyle6/



Meta http://srossross.github.io/Meta/html/index.html


Python code to xml https://pythonhosted.org/pyRegurgitator/

Pyupgrade https://github.com/asottile/pyupgrade/blob/master/pyupgrade.py

Auto type annotation


https://pypi.org/project/MonkeyType/ - by trace

Julia Volkova  12:39 PM
good tool if you have project with tests, but without type annotations https://pypi.org/project/MonkeyType/ package catch trace when you run your code (like in tests) with passing inside args and based on it generated type annotations and add it to code, and article about it https://instagram-engineering.com/let-your-code-type-hint-itself-introducing-open-source-monkeytype-a855c7284881 (also similar tools +-: https://github.com/dropbox/pyannotate, https://github.com/ambv/retype) (edited) 


LibCST https://github.com/Instagram/LibCST


https://github.com/gyermolenko/awesome-python-ast


Bowler 
https://github.com/facebookincubator/bowler


https://github.com/PyCQA/redbaron

https://github.com/Yelp/undebt

https://github.com/facebook/codemod

https://github.com/lihaoyi/macropy

https://github.com/llllllllll/codetransformer


https://github.com/hhatto/autopep8

https://github.com/PyCQA/baron

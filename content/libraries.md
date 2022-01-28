{% include navigation.html %}

# Library, Dependencies, Import

![image](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fajaytech.co%2Fwp-content%2Fuploads%2F2019%2F05%2Fpython_standard_libraries-1.png)

## Library
Libraries are collections of functions that you can use in your own program, usually the functions within the same library are related and work as a combined program.  There are generally more of them in higher-level languages like python and less in lower-level languages like C.

## Dependencies
If a function depends on another function to work, than that is a dependancy.  For example, a GUI program that edits images might require a base program like imagemagick, a well-known program that is a dependancy of many others.

## Import
Import is a python statement that 'imports' the functions of a library into the specific python file.  For example to import the functions of coollibrary.py to master.py, one would put 'import colllibrary' in master.py, usually at the top of the file.  One can also import specific functions from a library.  If I wanted to use the function coolfunc (within coollibrary.py) in master.py, I would use 'from coollibrary import coolfunc'.

# pytos_win_files
Python files to run pytos sdk in windows 10 environment. Only a hack. Will corrupt some pytos sdk functions.

This is an experimental hack to enable using the TOS SDK for python (pytos) with an Windows 10. It replaces files in python modules only runnable on linux, which are a requirement for using pytos. This will cause some of the pytos functionality to break! But a few functions may still be usable.

The pyinotify.py file is the file from the PyInotify project https://pypi.org/project/pyinotify/ with a few changes to use some of pytos functionality. PyInotify is released under MIT licence. 

Usage
Copy the files fcntl.py, pyinotify.py to the folder your python script resides in.

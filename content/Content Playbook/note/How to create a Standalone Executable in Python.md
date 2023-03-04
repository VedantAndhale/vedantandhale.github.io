---
title: "How to create a Standalone Executable in Python"
bookHidden: true
tags:
- Python
---
#### For Windows

* step 1 : check the terminal is in venv if not use cmd
```
set-executionpolicy remotesigned -scope currentuser
```
* step 2 : install pyinstaller 
* step 3 : then use cmd
```
pyinstaller --onefile --windowed --clean file_name.py
```

#### For Mac

* use platypus third platypus software

#### For Linux

similar to windows
if error of package install according to your distribution


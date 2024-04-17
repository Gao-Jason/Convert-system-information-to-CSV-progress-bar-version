# Convert-system-information-to-CSV-progress-bar-version

This is Python version 3.X

![License](https://img.shields.io/pypi/pyversions/3)


Using Python
====
Installable Python kits, and information about using Python, are available at [python.org](https://www.python.org/)。

project instruction
====
This is a program that can record the hard disk, CPU, and memory, and write the records into an Excel file through a CSV-like method, and if there is repeated execution on the day, it will also be marked additionally.
![1713260715143](https://github.com/Gao-Jason/Convert-system-information-to-CSV-progress-bar-version/assets/95835382/747a5c43-0cf9-4a33-8b15-3d032414f413)
![1713260724712](https://github.com/Gao-Jason/Convert-system-information-to-CSV-progress-bar-version/assets/95835382/1378b18a-de3d-43ac-bc5f-9d8e10939e53)

📦Install
pip automatic download & update
-------
This segment of code has already used several third-party libraries, but there is one more, the tqdm library, which is used to display progress bars within loops. If you don't have it installed on your system, you'll need to use pip to install it.
```
pip install tqdm
```
warning!!

''msvcrt'' is a Windows-specific library used for file locking, which may cause issues if your program runs on other platforms.

Additionally, if you intend to use file locking on Windows, msvcrt library is an option, but on other platforms, you may need to employ different methods to achieve file locking.

📦Pack
pip automatic download & update
-------
```
pip install pyinstaller
```
```
pyinstaller –F + Project name.py
```
This will generate a folder named dist in the current directory containing the packaged executable file.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

```
Python 3.x
```

### Installing

A step by step series of examples that tell you how to get a development env running

Install Python 3.x with pip

Install Pillow, a Python Imaging Library

```
pip install Pillow
```

Install PyInstaller, to generate .exe file (for Windows)

```
pip install pyinstaller
```


## Running the tests

### Linux, Mac OS X, BSD and most OSes except Windows
Turn script executable:

```
chmod +x photo-organizer.py
```

Call script inside a folder with photos:

```
./photo-organizer.py .
```

Call script inside a folder with archives:
```
./junkfiles.py .
```

### Windows

To run a test, call the script inside a folder with photos.

```
python photo-organizer.py .
```

Call script inside a folder with archives:
```
python ./junkfiles.py .
```

**For Windows in Context Menu:**

1. To generate *photo-organizer.exe* file to run on Windows.

```
pyinstaller -w -F photo-organizer.py
```

2. Add the keys on Registry or run *photo-organizer.reg*.
3. Copy .exe file on *C:\Program Files\Photo Organizer*
4. Add *C:\Program Files\Photo Organizer* in the *Path* on Windows Environment Variable.

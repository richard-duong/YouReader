# YouReader
Open Source Youtube Caption Reader

How to use
==========
This repository contains sample data extracted from YouTube. The directory structure is as follows:
```
YouReader/                  # custom python package for extracting captions
scripts/                    # setup scripts
tests/                      # unit and integration tests
data/                       # collected data
          example.csv       # example input file
```
<br>

### Steps (Prerequisites)
Before you can use and test code from this project, you will need the following installed on your system:
* [Python 3.7](https://www.python.org/downloads/)
* [pip - The Python Package Installer](https://pip.pypa.io/en/stable/installing/)
<br>

### Steps (First Time Installation)
To use this package, you'll have to generate a virtual environment to download the prerequisite python libraries.
If you have not generated the virtual environment yet, follow these steps.
1. Download and extract the code
2. Run the following commands:

```
Move to project directory
=========================
$ cd GuessTheClass

To generate a virtual environment
=================================
[Linux, MacOS]
$ chmod +x scripts/setup.sh
$ scripts/setup.sh

[Git Bash on Windows]
$ scripts/winsetup.sh

[Cmd Prompt on Windows]
> "scripts/setup.bat"

```
<br>

### Steps (General Setup)
After setting up the virtual environment for the first time,
Run these commands to load up the virtual environment before you start using our package.

```
Load the virtual environment
============================
[Linux, MacOS]
$ source env/bin/activate

[Git Bash on Windows]
$ source env/Scripts/activate

[Cmd Prompt on Windows]
> "env/Scripts/activate.bat" 


Disable the virtual environment
===============================
$ deactivate
```
<br>


If you have your own existing dataset that you want to test:
1. Put your YouTube links into "data/links.csv"
2. You can build your captions dataset using the example below

<p align="center">
          <img src="docs/example_program.png"/>
</p>
<br>


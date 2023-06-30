# PYTHON

## Python Virtual environment

`venv` (for Python 3) and `virtualenv` (for Python 2) allow you to manage separate package installations for different projects. They essentially allow you to create a “virtual” isolated Python installation and install packages into that virtual installation.

### venv

`venv` is a built-in module in Python 3, providing a simple and standardized way to create virtual environments specifically for Python 3

Check if Python virtual environment is installed

    python3 -m venv --help

Create a virtual environment

    python3 -m venv /path/to/new/virtual/environment

Activate the virtual environment

    cd /path/to/new/virtual/environment
    source bin/activate

Deactivate the virtual environment

        deactivate

List all the installed Python packages and their versions in the currently active Python environment.

    python3 -m pip list

Other ways to create a virtual environment

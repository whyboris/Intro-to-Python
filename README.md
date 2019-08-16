# Welcome

This is a repository to help you get started with Python.

## Quick start

On a Mac you already have Python 2 installed `python --version` in terminal will show you. We want Python 3 or later. Once installed `python3 --version` will confirm you have it once you have it installed.

Install requirements:

0. Install [git](https://git-scm.com/downloads)
1. Install [Python 3.6+](https://www.python.org/downloads/)
    - this will automatically install *pip* (_Pip Installs Python_ - a way to download [packages](https://pypi.org/))
2. Install [virtualenv](https://virtualenv.pypa.io/en/latest/installation/)
    - open your _terminal_ and run the command `pip install virtualenv`

Rather than install python packages (libraries) globally, we'll use [virtual environments](https://virtualenv.pypa.io/en/latest/userguide/):

0. Create a folder, go to it in your terminal
1. `virtualenv venv` ('venv' or 'env' is a convention, you can use whatever word)
2. `source venv/bin/activate` (you're now activating the virtual environment)

This is equivalent to _node_modules_ :sunglasses: -- run `which python` and you'll see the path points to inside your new folder. Now any time you `pip instal [anything]` it will be installed inside the virutal environemnt (inside the folder). To deactivate the environment, just enter `deactivate` in the terminal.

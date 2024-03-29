# Welcome

This is a repository to help you get started with Python.

## Quick start

On a Mac you already have Python 2 installed `python --version` in terminal will show you. We want Python 3 or later. Once installed `python3 --version` will confirm you have it once you have it installed.

Install requirements:

0. Install [git](https://git-scm.com/downloads)
1. Install [Python 3.6+](https://www.python.org/downloads/)
    - this will automatically install *pip* (_Pip Installs Python_ - a way to download [packages](https://pypi.org/))
2. Install [virtualenv](https://virtualenv.pypa.io/en/latest/installation/)
    - open your _terminal_ and run the command `pip3 install virtualenv`

Rather than install python [packages](https://pypi.org/) (libraries) globally, we'll use [virtual environments](https://virtualenv.pypa.io/en/latest/userguide/):

0. Create a folder, go to it in your terminal
1. `virtualenv venv` ('venv' or 'env' is a convention, you can use whatever word)
2. `source venv/bin/activate` (you're now activating the virtual environment)

This is equivalent to _node_modules_ :sunglasses: -- run `which python` and you'll see the path points to inside your new folder. Now any time you `pip instal [anything]` it will be installed inside the virutal environemnt (inside the folder). To deactivate the environment, just enter `deactivate` in the terminal.

## Jupyter

It's common to use [Jupyter](https://jupyter.org) to play with data, share or explain a procedure, or even to [run your company](https://medium.com/netflix-techblog/notebook-innovation-591ee3221233).

While inside the virtual environment, install with `pip install jupyterlab` or, as a common convention, by using the _requirements.txt_ file with
```sh
pip install -r requirements.txt
```

Now start Jupyter Lab in your terminal with `jupyter lab` and open the `showcase.ipynb` from within Jupyter Lab :tada:

### Pro tip

In your `.bashrc` (or `.zshrc` if you're on _zsh_, or the equivalent file you use with your terminal), add the alias:
```sh
alias py='python3'
```
You can also create a favorite environment in some convenient folder that you activate with some command, e.g.:
```sh
alias popo='source ~/.popo/venv/bin/activate'
```

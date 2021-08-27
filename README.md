# Installs
## Python
[Download](https://www.python.org/downloads/windows/) and install [`Python`](https://www.python.org/about/) itself. Be sure to check the box for ***Add to PATH variable***<br>
[Python 3.9.6 for Windows 64-bit](https://www.python.org/ftp/python/3.9.6/python-3.9.6-amd64.exe)

## git
[Download](https://git-scm.com/downloads) and install [git](https://git-scm.com/)
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

`git` is used by major tech companies and lone individuals alike to manage their code. [These videos](https://git-scm.com/videos) are helpful for some more basic information about version control and `git`. There's also a [free e-book](https://git-scm.com/book/en/v2) that walks through all of the main `git` operations.

# File Setup
## Python Virtual Environment
- Launch `Powershell` or `cmd`. It should start in your Windows user folder: `C:\Users\...`
- Create a folder to store virtual environments<br>
`mkdir Envs`
- Create a virtual environment (`venv`) for your project. `first_venv` can be replaced with any other name<br>
`python -m venv .\Envs\first_venv`
- Activate the virtual environment<br>
`& .\Envs\first_venv\Scripts\activate`

#### References
- [Virtual Environments and Packages](https://docs.python.org/3/tutorial/venv.html)
- [venv — Creation of virtual environments](https://docs.python.org/3/library/venv.html)
- [Python Virtual Environments: A Primer](https://realpython.com/python-virtual-environments-a-primer/)

## Folder Setup
- Navigate to the folder that you plan to store your files in, usually in somewhere in `C:\Users\Documents\...`<br>
    - You can change folders with the `cd` command
    - `.\` indicates the current folder
    - You can use auto completion on the paths using the `TAB` key<br>
`cd .\D` can be auto-completed to `cd .\Documents\`
- Clone the `git` repository into the folder.<br>
`git clone https://github.com/jsl12/office_training`

#### References
- [Git Basics - Getting a Git Repository](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository), see *Cloning an Existing Repository*

## Install Packages
Install all the packages using a single command: `pip install .\office_training\requirements.txt`. `pip` installs packages (pre-written Python code) by downloading them from [PyPI](https://pypi.org/), the Python Package Index

#### References
- [Install multiple packages using a requirements file](https://pip.pypa.io/en/stable/getting-started/#install-multiple-packages-using-a-requirements-file)

## Start [Jupyter Lab](https://jupyter.org/about)
Start Jupyter Lab with the command `jupyter lab`. Jupyter Lab will then open in a browser window<br>
[Try out Jupyter Lab](https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab/tree/demo)
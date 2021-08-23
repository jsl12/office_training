# Installs
## Python
<a href="https://www.python.org/downloads/windows/">Download</a> and install <a href="https://www.python.org/about/">`Python`</a> itself. Be sure to check the box for "Add to PATH variable"<br>
<a href="https://www.python.org/ftp/python/3.9.6/python-3.9.6-amd64.exe">Pyhon 3.9.6 for Windows 64-bit</a>

## git
<a href="https://git-scm.com/downloads">Download</a> and install <a href="https://git-scm.com/">`git`</a><br>
> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

`git` is used by major tech companies and lone individuals alike to manage their code. <a href="https://git-scm.com/videos">These videos</a> are helpful for some more basic information about version control and `git`. There's also a 
<a href="https://git-scm.com/book/en/v2">free e-book</a> that walks through all of the main `git` operations.

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
- <a href="https://docs.python.org/3/tutorial/venv.html">Virtual Environments and Packages</a>
- <a href="https://docs.python.org/3/library/venv.html">venv — Creation of virtual environments</a>
- <a href="https://realpython.com/python-virtual-environments-a-primer/">Python Virtual Environments: A Primer</a>

## Folder Setup
- Navigate to the folder that you plan to store your files in, usually in somewhere in `C:\Users\Documents\...`<br>
    - You can change folders with the `cd` command
    - `.\` indicates the current folder
    - You can use auto completion on the paths using the `TAB` key<br>
`cd .\D` can be auto-completed to `cd .\Documents\`
- Clone the `git` repository into the folder.<br>
`git clone https://github.com/jsl12/office_training`

#### References
- <a href="https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository">Git Basics - Getting a Git Repository</a>, 
see <i>Cloning an Existing Repository</i>

## Install Packages
Install all the packages using a single command: `pip install .\office_training\requirements.txt`. `pip` installs packages (pre-written Python code) by downloading them from <a href="https://pypi.org/">PyPI</a>, the Python Package Index

#### References
- <a href="https://pip.pypa.io/en/stable/getting-started/#install-multiple-packages-using-a-requirements-file">Install multiple packages using a requirements file</a>

## Start <a href="https://jupyter.org/about">Jupyter Lab</a>
Start Jupyter Lab with the command `jupyter lab`. Jupyter Lab will then open in a browser window<br>
<a href="https://mybinder.org/v2/gh/jupyterlab/jupyterlab-demo/master?urlpath=lab/tree/demo">Try out Jupyter Lab</a>
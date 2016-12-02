# PythonVirtualEnv
Python virtual environments for the development of matrix games

## Installation

 1. Create the following directory:

    `C:\PythonVirtualEnv\MatrixGames`

    If it already exists, make sure it is empty.

    **Attention:** You **must** clone the repository to `C:\PythonVirtualEnv\MatrixGames`, because the path is hard coded in all binaries (e.g. pip.exe).


 2. Change in to the directory and clone into it:
    - Via HTTPS: `git clone https://github.com/MatrixGamesHub/PythonVirtualEnv.git . `
    - Via SSH: `git clone git@github.com:MatrixGamesHub/PythonVirtualEnv.git  . `

    **Attention:** The point at the end is important and ensures that GIT clones into the current directory!
 3. You also need a [Python 3.4][1] installation. It is recommended to install it to `C:\Python34`. If You choose another directory, then you have to change the `home` variable in `C:\PythonVirtualEnv\MatrixGames\pyvenv.cfg`.


## Usage

The virtual environment contains the binary of the python interpreter, which you must use, if you want to run scripts from the Matrix Games project.

 - If you are using Eclipse, create a new interpreter (`Window -> Preferences -> PyDev -> Interpreters -> Python Interpreters`) that points to the binary `C:\PythonVirtualEnv\MatrixGames\Scripts\python.exe`.

 - If you are developing in a console, you can activate the virtual environment by running the `C:\PythonVirtualEnv\MatrixGames\Scripts\activate.bat`. This will adjust the `path `environment variable so you can run a script as usual with `python script.py`.

 - If you do not want the activation, you can simply run a script by using the full path to the interpreter: `C:\PythonVirtualEnv\MatrixGames\Scripts\python script.py`



[1]: https://www.python.org/ftp/python/3.4.4/python-3.4.4.msi

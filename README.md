# PythonVirtualEnv
Python virtual environments for the development of matrix games

**Attention:** You **must** clone the repository to `C:\PythonVirtualEnv\MatrixGames`, because the path is hard coded in all binaries (e.g. pip.exe).

**Usage**

 1. Create following directory:
    `C:\PythonVirtualEnv\MatrixGames`
    If it already exists, make sure it is empty.

 2. Change in to the directory and clone into it:
    - Via HTTPS: `git clone https://github.com/MatrixGamesHub/PythonVirtualEnv.git . `
    - Via SSH: `git clone git@github.com:MatrixGamesHub/PythonVirtualEnv.git  . `

    **Attention:** The point at the end is important and ensures that GIT clones into the current directory!
 3. You also need a [Python 3.4][1] installation. It is recommended to install it to `C:\Python34`. If You choose another directory, then you have to change the `home` variable in `C:\PythonVirtualEnv\MatrixGames\pyvenv.cfg`.

  [1]: https://www.python.org/ftp/python/3.4.4/python-3.4.4.msi

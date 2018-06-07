# Setup Python and Jupyter with Micropython Kernel

## Install Python 3

### Checking if Python is Installed

Open command prompt on Windows or a terminal on MacOSX and Linux and enter `python`. If a repl opens and says
"Python 3.X.X" then it is installed. If it says "Python 2.X.X" try entering `python3` instead. If a repl does
not open proceed to the "Installing Python" section.

#### Installing Python

After installing python on your system refer back to the "Checking if Python is Installed" section above.

#### Windows

Download the appropriate executable installer from [python.org]("https://www.python.org/downloads/windows/").
Follow the installation instructions making sure to check "add to PATH".

#### MacOSX

To install python on MacOSX enter:

`brew install python`

#### Linux

To install python on debian based linux distributions enter:

`sudo apt install python`

If you have another distribution, simply use its package manager instead.

## Install Jupyter

After installing python you should also have pip installed. To install jupyter with pip enter the following command
into your command prompt or terminal. You may need to use "sudo" on Linux and MacOSX or use "pip3" instead of pip.

`pip install jupyter`

## Install Micropython Kernel

Follow the installation section of goatchurchprime's jupyter_micropython_kernel
[here]("https://github.com/goatchurchprime/jupyter_micropython_kernel"). Make sure to use the correct version of python and pip.

## Check if Jupyter and the Micropython Kernel is Working

Download the [esp8266 repository]("https://github.com/MicroNotebook/esp8266-examples") and open a terminal or command prompt
in the repository's directory. Now enter the following to launch jupyter.

`jupyter notebook`

Once inside jupyter, open the "serial_test.ipynb" notebook and follow the directions inside. Make sure that the Micropython kernel
is selected rather than the Python kernel. If you are able to successfully run all of the cells in the notebook, then everything is
working properly.
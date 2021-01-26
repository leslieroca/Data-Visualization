# Data-Visualization

On this project we are going to be exploring data through visual representations using Python.


# Installing matplotlib

# On Linux
If you’re using the version of Python that came with your system, you can use your system’s package manager to install 
matplotlib using just one line:

$ sudo apt-get install python3-matplotlib

If you’re running Python 2.7, use this line:

$ sudo apt-get install python-matplotlib

If you installed a newer version of Python, you’ll have to install a few
libraries that matplotlib depends on:

$ sudo apt-get install python3.5-dev python3.5-tk tk-dev $ sudo apt-get install libfreetype6-dev g++

Then use pip to install matplotlib:
NOTE: If you don't have pip installed, got to this page https://vgkits.org/blog/pip3-macos-howto/ and follow the steps.

$ pip install --user matplotlib


# On Mac
Apple includes matplotlib with its standard Python installation. To check whether it’s installed on your system, open a 
terminal session and try import matplotlib. If matplotlib isn’t already on your system and you used Homebrew to install 
Python, install it like this:
NOTE: If you don't have pip installed, got to this page https://vgkits.org/blog/pip3-macos-howto/ and follow the steps.


$ pip install --user matplotlib

n o t e : You might need to use pip3 instead of pip when installing packages. Also, if this command doesn’t work, you 
might need to leave off the --user flag.


# Testing matplotlib
After you’ve installed the necessary packages, test your installation by startmating a terminal session with the python 
or python3 command and importing matplotlib:

$ python3

import matplotlib

If you don’t see any error messages, just ">>>", then matplotlib is installed on your system, and you can move on to the 
next section.
testing mat


# Installing Pygal
On Linux and OS X, this should be something like:

pip install --user pygal

On Windows, this should be:

python -m pip install --user pygal

# Note
You may need to use the command pip3 instead of pip if you are using python3, and if the command still doesn’t work you 
may need to leave off the --user flag.
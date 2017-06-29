## INSTALLATIONS

If you have a Mac

Macs come with Python 2.7 pre-installed. Do not be fooled, though. If you try to use this Python and install things you may end up in tears, because Macs are good at many things but not at package management. That means, if you don’t do things the “right way” from the start, you will at some point or the other end up with two versions of python floating around somewhere and libraries that refuse to import.

Thankfully, Homebrew is a great free and open source package management system. You might have also heard of MacPorts or other alternatives, but Homebrew is the best in my experience.

Todo:
Optional: Download iTerm2, a better terminal for Macs.
Go to https://brew.sh/ and follow the instructions to download Homebrew.

Installing Python 3 the Right Way
Now you are ready to install Python the “right way”. Follow the Hitchhiker’s guide to Python.

Installing tools: iPython, Pandas, Numpy, SciPy

You may encounter hiccups in these steps, but try the following:

brew tap homebrew/science # a lot of cool formulae for scientific tools
brew tap homebrew/python # numpy, scipy, matplotlib, …
brew update && brew upgrade


Then, install JuPyter, a wonderful open-source browser app that lets you visualize results as you code, write narrative, and share:

pip3 install jupyter -U

Finally install Pandas, a python library I like to use for data analysis. It’s great for small-to-medium datasets and the paradigms are based off the R programming language, which makes it easy to switch between.

pip3 install pandas

Now test that everything is properly installed.

Fire up a terminal window, and type: 
iPython

Which will begin a python session in the terminal. 
Then type:

import numpy
import scipy
import matplotlib
import pandas


Does everything work?


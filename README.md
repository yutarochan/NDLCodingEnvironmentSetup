# Setting Up Your Coding Environment
 
## Setting up Anaconda

### What is Anaconda
The Anaconda platform is used for package management, collaberative projects, and handling virtual environments. In Nittany Data Labs, we use Anaconda to handle all of the packages you have been using in your DataCamp courses. The packages you have been importing at the head of your programs, such as ```pandas``` and ```numpy```,  have to be installed on your computer before you can begin using them in all of the Data Science applications you write. When you install Anaconda on your system, you install of the packages and their necessary dependenciesn so when you begin writing full scale Machine Learning applications, you never have to worry about finding the package online yourself, Anaconda comes to the rescue.

#### Which Python do I have?
* For Mac OS or Linux, open Spotlight and search Terminal. Open Terminal and type ```which python```
    * If you do not have Python, download [Python 3.6](https://www.python.org/ftp/python/3.6.3/python-3.6.3-macosx10.6.pkg)
* For Windows, run Command Prompt and type ```python```
    * If you do not have Python, download [Python 3.6](https://www.python.org/ftp/python/3.6.3/python-3.6.3.exe)
   
#### Mac OS

* [Python 3.6 Anaconda Installer](https://repo.continuum.io/archive/Anaconda3-5.0.0-MacOSX-x86_64.pkg)
* [Python 2.7 Anaconda Installer](https://repo.continuum.io/archive/Anaconda2-5.0.0-MacOSX-x86_64.pkg)

#### Windows

* [Python 3.6 Anaconda Installer](https://repo.continuum.io/archive/Anaconda3-5.0.0-Windows-x86_64.exe)
* [Python 2.7 Anaconda Installer](https://repo.continuum.io/archive/Anaconda2-5.0.0-Windows-x86_64.exe)

#### Linux

* [Python 3.6 Anaconda Installer](https://repo.continuum.io/archive/Anaconda3-5.0.0.1-Linux-x86_64.sh)
* [Python 2.7 Anaconda Installer](https://repo.continuum.io/archive/Anaconda2-5.0.0.1-Linux-x86_64.sh)

#### Verify that Anaconda is Installed
* Run ```conda --version``` to verify that you have installed Anaconda correctly on your system
* Update Anaconda with ```conda update conda```
    * If a new conda version is available, ```Proceed ([y]/n)?``` type ```y```
* On your Terminal or Command Prompt, type ```python``` and now you are in a Python Shell, similar to the one you have been using on DataCamp!
    * type ```import pandas as pd``` and ```import numpy as np```
    * These might take a while (these packages are huge!)
    * Play around with them on your computer similar to how you do in DataCamp!

There you go, now you have access to all of the packages that you have been learning about on DataCamp! 


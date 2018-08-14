# GettingStarted
Instructions for getting started with [python](#Python), [git/GitHub](#git/GitHub), and [LaTeX](#LaTeX).

# Python

## Installing Python
This is easiest on Linux/MacOS but can be done on Windows as well. If you are on Windows, the following instructions should work but you may find some useful information here: https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444

Download the **Python 3.6** (NOT 2.7) anaconda installer here: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)

Run the installer (this may take a while)

Install a few useful packages which are not included by default by running the following lines in the terminal

```bash
conda install -c astropy aplpy astroplan astroquery ccdproc photutils specutils
pip instal emcee
```

## Python Tutorials
Code from astronomical Python tutorials developed here at UT Austin as well as links to online tutorials can be found in the [PythonTutorials](https://github.com/UTAustinAST376Fall2018/PythonTutorials) repository.

## Useful Python documentation links

Astropy: 
* http://www.astropy.org
* http://docs.astropy.org/en/stable/

APLPy
* http://aplpy.github.io/index.html

astroplan
* https://astroplan.readthedocs.io/en/latest/

astroquery
* https://astroquery.readthedocs.io/en/latest/

ccdproc
* https://ccdproc.readthedocs.io/en/latest/

photutils
* https://photutils.readthedocs.io/en/stable/index.html

specutils
* https://specutils.readthedocs.io/en/latest/

emcee
* http://dfm.io/emcee/current/

# git/GitHub

## Installing Git

Git is a version control tool. It helps you keep track of changes you make to your code. This allows you to roll back changes you have made if you break your code. GitHub is a website which interfaces with git to provide cloud hosted repositories. This allows multiple people to work on a project at the same time and share or publish your code. GitHub also provides other tools such as webpages, wikis, issue trackers, 

Git is installed on the Linux/MacOS command line by default so you don't have to do any installation! If you are running Windows you can follow the instructions here: https://hackernoon.com/install-git-on-windows-9acf2a1944f0 (It is as simple as downloading and running an installer)

Alternatively you can download a GUI application for MacOS or Windows here: https://desktop.github.com

Some further configuration can be done to streamline your workflow such as saving your GitHub username, email, and password:
* https://help.github.com/articles/setting-your-username-in-git/
* https://help.github.com/articles/setting-your-commit-email-address-in-git/
* https://help.github.com/articles/caching-your-github-password-in-git/

## Git/GitHub Resources, Tutorials, and cheat sheets

* https://help.github.com/articles/git-and-github-learning-resources/
* https://guides.github.com
* http://gitimmersion.com
* http://try.github.io
* https://education.github.com/git-cheat-sheet-education.pdf
* https://www.git-tower.com/blog/git-cheat-sheet/
* https://git-scm.com/docs/gittutorial
* https://ottostruve.github.io/gsps/slides/factor_git.pdf

# LaTeX

The easiest way to use the LaTeX document preparation software package is via https://www.overleaf.com. The AASTeX Template which you will be required to format your project reports in can be found here: https://www.overleaf.com/latex/templates/aastex-template-for-submissions-to-the-astrophysical-journal/bpkjwktvsqwp#.W3MmOC3MwkU

If you would like to run LaTeX on your personal computer you will need to install LaTeX (warning: it is VERY large) and the AASTeX style sheets. Instructions and installers for Linux/MacOS/Windows can be found here: https://www.latex-project.org/get/
Then follow the instructions to install AASTeX here: [https://journals.aas.org/authors/aastex.html#_download](https://journals.aas.org/authors/aastex.html#_download)
That page also has links to guides on specific AASTeX commands and conventions.

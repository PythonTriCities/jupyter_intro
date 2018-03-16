# PythonTriCities demo jupyter notebooks.

This demo is how jupyter notebooks work.

### Prerequisites

* python3 (Python is an open source general progarmming language https://wiki.python.org/moin/)
* git (Git is a version control system https://en.wikipedia.org/wiki/Git)
* A default web browser, any one will do

## Getting Started

1. Follow the guidelines here to satisfy the getting started prerequisites.
	* https://github.com/PythonTriCities/starthere
  
### Clone this repository

```
git clone https://github.com/PythonTriCities/jupyter_intro.git
```
* If you had trouble with the git install or just want to download the files as a zip, click this link [starthere](https://github.com/PythonTriCities/jupyter_intro/archive/master.zip)

### The next 2 steps are optional but recommended

3. Create the virtual environment if it doesn\'t exist:
  * [What/'s a virtual environment?](https://docs.python.org/3/library/venv.html)

* On Linux/Mac it is: python3 -m venv /path/to/new/virtual/environment

 * I like to set the path to be in the directory with a folder that shows the version of Python that I am running, so I include the python version I am using in the path

```
python3 -m venv ./.venv/python3.6
```
* On Windows it is c:\>c:\Python35\python -m venv c:\path\to\myenv

```
c:\>c:\Python35\python -m venv c:\path\to\myenv
```

4. Start your virtual environment.

* Linux/Mac:

```
source ./.venv/bin/activate
```

* Windows:

```
c:\path\to\myenv\Scripts\activate.bat
```
 

 * and then for both Linux/Mac and Windows import the requirements file
```
pip install -r requirements.txt
```

5. Test that it is not legacy Python, ie 2.7

```
python --version
```
* You should see something like this:
```
Python 3.6.4
```

6. Now start the jupyter notebook by entering
```
jupyter notebook NotebookOne.ipynb
```

## Running the tests

No test for this script, but we will cover that in later examples

## Versioning

Use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/PythonTriCities/jupyter_intro.git/tags).

## Authors

* **John M** - *Initial work* - [TechSolX](https://github.com/techsolx)

See also the list of [contributors](https://github.com/PythonTriCities/jupyter_intro/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Help from the internets, stackoverflow, users group members, etc...

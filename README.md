# seattle-crime-analysis

## **Introduction**

This jupyter notebook `main.pynb` file is an anaylsis of Seattle, Washington's crime data from the police department from 2008 through 2020. This project was developed to identify crime trends by date and by neighborhood. One can access total crime data and/or specific crimes, in the whole city and/or specific neighborhoods. This project was also created to identify changes in crime trends over time. Developers used `.csv` files along with many pandas libraries to clear and view graphs of the data. A new user could upload their own data and use these calculations to analyze it.

## **Technologies**
Python 3.10 and the following packages:

* [csv](https://docs.python.org/3/library/csv.html) -- Used to store all of our SPD data

* [fire](https://github.com/google/python-fire) - *version 0.4.0* - This allows us to execute any fuction defined in a python file, using the terminal/ Command Line Interface so that you can call the function while on the terminal.

* [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) - *version 3.4.4* - Used to create and share documents that contain live code, equations, visualizations and narrative text.

* [matplotlib](https://matplotlib.org/) - For the visualization of crime data.

* [numpy](https://numpy.org/install/) - This provides the ability to work with arrays and use different mathematical calculations on arrays.

* [pandas](https://pandas.pydata.org/docs/) - For the analysis of crime data.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - *version 1.0.1* - This was used to locate through the directory or file path. Also, it converts a string and converts that supplied string as a PosixPath that can be utilize by other functions such as reading or writing files to csv files.

* [python-dotenv library](https://pypi.org/project/python-dotenv/) - *version 0.17.1* - This enables the user to read key-value pairs from an .env file and set them as an environment variables.

* [PyVizlot](https://pyviz.org/) -  Python visualization package that provides a single platform for accessing multiple visualization libraries. Two of the libraries are:

  * [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Introduction.html) - *version 0.7.2* - For the interactive visualization of the crime data.

  * [plotly.express](https://plotly.com/python/plotly-express/) - *version 4.13.0* - For the visualization of crime data.

* [questionary](https://github.com/tmbo/questionary) - *version 1.9.0* - For interactive user prompts and dialogs. This was used to create interactive question inputs/options in the terminal for users to answer.

* [Sqlalchemy ](https://anaconda.org/anaconda/sqlalchemy) - *version 1.3.20* - This is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.

* [sys Module](https://docs.python.org/3/library/sys.html) - This was used specifically for its sys.exit()funciton which was used to exit the program back to its command prompt. The sys module provides functions and variables used to manipulate different parts of the Python runtime environment. You will learn some of the important features of this module here.

* [Voilà](https://github.com/voila-dashboards/voila) - This will allow us to view our crime analysis on the web browser.

## **Installation Guide**
On the terminal, under the conda dev environment, install the following packages and dependencies before running the crime analysis application
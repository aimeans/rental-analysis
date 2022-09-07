A jupyter notebook analysis of San Francisco rental properties with interactive visualizations. First we take curated census data and read it into a pandas dataframe. Next, we prepare it by cleaning and passing the data through various filters. Then we compose different plots and views to show sale price per square foot and gross rent trends in San Francisco from 2010-2016.
## Technologies
Language: Python 3.9.12
Libraries Used: 
[Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For the creation and visualization of Data Frames

[Jupyter Labs](https://jupyter.org/) - An ipython kernel for interactive computing in python

[PyViz hvPlot](https://hvplot.holoviz.org/index.html) - A high level python library for data visualization and plotting

[PyViz GeoViews](https://geoviews.org/) - A python library used for viewing geographical, meteorological, and oceanographic datasets
## Installation Guide
You will need to have pandas, Holoplot Geoviews, and jupyter labs installed in your virtual environment.
For a full install activate a conda development environment and run in Terminal:
```python
    conda install pandas
    conda install jupyterlab
    conda install -c pyviz hvplot geoviews
```

Check the to make sure everything has been installed properly
```python
    conda list hvplot
    conda list geoviews
```

---
## Usage
To run this in a Jupyter Lab notebook you will need to navigate in your terminal to the place where you have exported the files for this project.
Next perform the following actions in the terminal:
![Jupyterlab](readme_images/Jupyterlab.png)

This will open a Jupyter labs notebook in your default browser.

Next open **'san_francisco_housing.ipynb'** and click the double arrow to run the notebook or run each cell individually whatever you prefer.

## Contributors
created by Austin means while in UW Fintech Bootcamp.
Contact info:
Email: Austinmeans92@gmail.com
Github: (https://github.com/aimeans)

## License
[MIT]

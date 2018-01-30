# Analyzing-NYC-High-Schools-SAT-Results
One of the most controversial issues in the U.S. educational system is the efficacy of standardized tests, and whether they're unfair to certain groups. Given my prior knowledge of this topic, investigating the correlations between SAT scores and demographics seemed like an interesting angle to take. I could correlate [SAT scores](https://en.wikipedia.org/wiki/SAT) with factors like race, gender, income, and more.

The SAT, or Scholastic Aptitude Test, is an exam that U.S. high school students take before applying to college. Colleges take the test scores into account when deciding who to admit, so it's fairly important to perform well on it.

The test consists of three sections, each of which has 800 possible points. The combined score is out of 2,400 possible points (while this number has changed a few times, the data set for our project is based on 2,400 total points). Organizations often rank high schools by their average SAT scores. The scores are also considered a measure of overall school district quality.

New York City makes its [data on high school SAT scores](https://data.cityofnewyork.us/Education/SAT-Results/f9bf-2cp4) available online, as well as the [demographics for each high school](https://data.cityofnewyork.us/Education/DOE-High-School-Directory-2014-2015/n3p6-zve2).

## Getting Started

Download the [Jupyter notebook](https://github.com/arjunchndr/Analyzing-NYC-High-Schools-SAT-Results/blob/master/Analyzing%20NYC%20Schools%20SAT%20Results.ipynb) if you have all the dependencies listed below. 

Plotly graphs are not visible on GitHub hosted Jupyter notebook - as iFrames are not supported. You can view the notebook containing the interactive Plotly graphs [here](http://nbviewer.jupyter.org/github/arjunchndr/Analyzing-NYC-High-Schools-SAT-Results/blob/master/Analyzing%20NYC%20Schools%20SAT%20Results.ipynb). 

Certain Folium maps are not being displayed on the Github hosted as well as nbviewer hosted notebooks. They can be accessed here:
* [School District Level Mapping of SAT Scores](https://github.com/arjunchndr/Analyzing-NYC-High-Schools-SAT-Results/blob/master/sat_score.html) 
* [School District Level Mapping of Percentage of English Language Learners](https://github.com/arjunchndr/Analyzing-NYC-High-Schools-SAT-Results/blob/master/ell_percent.html)  
* [School District Level Mapping of Safety and Respect score based on student responses](https://github.com/arjunchndr/Analyzing-NYC-High-Schools-SAT-Results/blob/master/saf_s_11.html) 

## Built With

* [Anaconda](https://www.anaconda.com/download/) - Distribution pre-installed with Python and its associated packages
  * [Python 3.6.3](https://www.python.org/downloads/) 
  * [Pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) 
  * [Jupyter 5.1.0](http://jupyter.org/install.html) 
  * [Plotly](https://plot.ly/) 
  * [Folium](https://github.com/python-visualization/folium)


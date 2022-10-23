# FordGoBike Dataset Exploration

![Contributors](https://img.shields.io/github/contributors/walidsi/ford-go-bike?style=plastic)
![Forks](https://img.shields.io/github/forks/walidsi/ford-go-bike)
![Downloads](https://img.shields.io/github/downloads/walidsi/ford-go-bike/total)
![Stars](https://img.shields.io/github/stars/walidsi/ford-go-bike)
![Licence](https://img.shields.io/github/license/walidsi/ford-go-bike)
![Issues](https://img.shields.io/github/issues/walidsi/ford-go-bike)

### Goal
The bicycle-sharing service has gained popularity in major cities across the globe. They allow people in metropolitan areas to rent bicycles for short trips usually within 30 minutes. Ford GoBike is a bike sharing service that operates in the San Frnacisco Bay area.
In this project, we perform and exploratory and explanatory data analysis of the the Ford GoBike dataset. The goal is to figure out what variables possess the most influential power on a bike sharing service. We aim to answer the followinq questions among others:
- When are most trips taken in terms of time of day, day of the week, or month of the year?
- How long does the average trip take?
- Does the above depend on if a user is a subscriber or customer?

### Dataset
The FordGoBike dataset contains approx. 180k records. They includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset includes information like:
- Trip start/end date and time.
- Trip duration.
- Start / end station co-ordinates.
- Biker age

### Process

### Summary of Findings
- The vast majority of trips are taken by males.
- The vast majority of trips are for cyclists not enrolled in the <b>Bike Share for All</b> program.
- The majority of trips are in San Francisco.
- Most of our cyclists are in the 25-34 age group.
- Most trips are taken on Thursdays.
- We see a sharp decline in the number of trip during the weekend.
- The average trip duration is 12 minutes.
- ALL "Bike Share for All" trips are taken by Subscribers. Most of their trips are taken in San Jose followed by San Francisco and then Berkeley.
- Most of the trips start at 8AM and at 5PM which is a strong sign that cyclists use  our bikes to commute to/from work.

### Install
This project requires **Python 3.x** and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [geopy](https://geopy.readthedocs.io/en/stable/)
- [folium](https://python-visualization.github.io/folium/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Code
Code is provided in the `fordgobike_exploration.ipynb` notebook file.

### Run
In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook fordgobike_exploration.ipynb
```  
or
```bash
jupyter notebook fordgobike_exploration.ipynb
```

This will open the iPython Notebook software and project file in your browser.

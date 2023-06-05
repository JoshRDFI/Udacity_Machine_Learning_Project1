# Data Scientist Nanodegree
# Supervised Learning
## Project: Finding Donors for CharityML


This project requires **Python 3.9.15** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

I used [Anaconda](https://www.continuum.io/downloads) for this project, after updating to ensure all libraries are at the most recent version. The only potential future issue is Jupyter 7. It's possible this upcoming update may break some of the current notebook. At the time of completion, every feature worked as expected. 

This project uses modified census dataset consisting of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income). 

The focus of the project is to use 4 supervised algorithms, one of which is a naive predictor, on the data to determine which persons make over $50,000.00 per year and are therefore most likely to donate to charity. The main file is the Jupyter notebook called finding_donors.ipynb.



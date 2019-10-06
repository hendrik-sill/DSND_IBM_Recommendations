# DSND_IBM_Recommendations

### Introduction and Motivation
I did this project as a part of the Udacity Data Scientist Nanodegree. 

The goal of the project is to apply different approaches to recommendations on data supplied by IBM. More specifically,
**rank-based recommendations**, **user-user based collaborative filtering**, and a **matrix factorisation** based approach
are contained in the Jupyter notebook. 

I have **not** yet implemented **content based recommendations**.

### Overview and Summary

This project starts off with an exploratory analysis of the data provided by IBM. The data contains information on interactions of users
with articles on the IBM Watson Studio platform.

Following the exploratory data analyis, **rank-based recommendations**, **user-user based collaborative filtering**, and a **matrix factorisation** based approach are set up in small steps by defining a number of different functions. The results of these approaches
are tested against expected outputs provided by Udacity.

In particular the last section with the typical cold start problem serves as a good example of how a good recommendation system will
need to make use of a number of different approaches to provide good recommendations to users.

### Required Packages

I used Python 3.6.7 (Anaconda distribution) for this project. If you are using Anaconda, you will not need to install additional packages.
On other Python distributions, you may also need to install Pandas, Numpy, Matplotlib, and Seaborn.

### Instructions:

In order to run the notebook, just follow the usual steps, i.e. start a Jupyter notebook server on your local machine.

### Acknowledgements and Credits

This project is primarily based on what I have learned in the Udacity Data Scientist Nanodegree. A template of the Jupyter notebook with gaps to be filled with code was supplied by Udacity. Furthermore, credit has to be given to IBM for providing the data used in this project.

### License

This project is licensed under the GNU General Public License Version 3.

Course mini-project for CMPUT 551: Introduction to Machine Learning, for the Fall 2017 semester at the University of Alberta.

It is an empirical study of a number of matrix factorization techinques for interpolating missing data within an 

electrodiagnostic nerve data set. See the paper for details.


##############
PYTHON VERSION
##############
2.7.12

###############
DEPENDENCIES
###############
#I ran into trouble installing cvxopt, so I ended up using pip, and have saved all the needed modules as a requirements file
pip install -r requirements.txt

#I'm using virtual environments to keep dependencies between projects separate: https://virtualenv.pypa.io/en/stable/
#Might be worth looking into, though YMMV

#You can also specify which version of python you want the environment to use: https://stackoverflow.com/questions/1534210/use-different-python-version-with-virtualenv


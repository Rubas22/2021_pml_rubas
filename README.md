# 2021_pml_rubas
This is my repo for the course ML at CCM UNAM  
All progress is going to be saved here.

For this course, we follow the book: C. Muller, Andreas and Guido, Sarah. "Introduction to Machine Learning with Python". United States of America., O’Reilly Media, Inc., 1005 Gravenstein Highway North, Sebastopol, CA 95472., October 2016.

In order to run the code you'll need some libraries. You can run:  
`pip install numpy scipy matplotlib ipython scikit-learn pandas`  
`pip install mglearn`  
in your terminal to set up the necessary requirements.

To see the tree.dot documents generated in project/erythemato_squamous_analysis.ipynb it is necessary to do:  
`pip install graphviz`  
`sudo apt-get install graphviz`

All files have been run and tested with Pyhton 3.8.10

Inside python-novice-gapminder-data folder you'll find exercices that correspond to each lecture, as well as a data folder with all necessary data.

Inside homework folder there are two files with my solutions to homework.

In expo folder there is the slices with the topic I presented as part of the course.

As final project, a dataset is analyzed with various classifiers. Such dataset contains records on patients with one out of six skin diseases; for more details pleas read /project/data/dermatology.names. The goal is to compare different models which aim to diagnose the type of Eryhemato-Squamous. Eight of the records were omitted in the .csv file since they lack the "age" field. The original dataset was gotten from "https://archive.ics.uci.edu/ml/datasets/Dermatology" and I included a paper where you can see how this dataset was originally used. 

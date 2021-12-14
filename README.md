# 2021_pml_rubas
This is my repo for the course ML at CCM UNAM.

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

In expo folder there are two presentations. One of them has the slices with the topic I presented as part of the course and the other is the presentation of my final project.

As final project I implemented decision trees algorithms. The aim was to get a playable model to diagnose erythemato-squamous diseases (ESD). Such model allow us to understand how some clinical and histopatological features are related to the illnesses. The dataset that was used contains records on patients with one out of six skin diseases; for more details please read /project/data/dermatology.names. The original dataset was gotten from "https://archive.ics.uci.edu/ml/datasets/Dermatology" and I included a paper where you can see how this dataset was originally used.
All this is located in the project folder.

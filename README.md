# Introduction to Python for Pattern Recognition (EE468/EE9SO29/EE9CS729)
## 22/10/2019

This repository contains a brief introduction to Python for pattern recognition. The tutorial is designed to provide tools and help students of pattern recognition module (EE468/EE9SO29/EE9CS729, EEE dept. at [Imperial College London](https://www.imperial.ac.uk/)) to complete their coursework. It's not an exhaustive tutorial on Python and it's tailored for this course, complementing the theory lectures.

This tutorial covers:

1. Basic Python: Some basic data structures, loops and functions.
2. Numpy: arrays, array indexing, datatypes, array math, broadcasting.
3. Linear algebra with Numpy: basic operations, determinants, inverses, eigenvalues and eigenvectors.
4. Data visualisation: plotting, subplots, images, confusion matrix
5. Images: loading and manipulating face data for coursework 1, intro to opencv (optional)
6. SVM: an example of using super vector machines with scikit.

The tutorial runs on [Jupyter Notebook](http://jupyter.org/):

``The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, data visualization, machine learning, and much more.``

**Why Jupyter Notebook?**

Simply put, it's a great way to share Python code for scientific computing. Check out this [*Nature* article](https://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261) or this [introduction](https://unidata.github.io/online-python-training/introduction.html) for a bit of history.

If you submit your code on your coursework 1 report feel free to use any format, including notebook `.ipynb`, standard Python `py` format and Matlab. For coursework 2 please read the instructions on the coursework 2 guidelines. 

### How can I run the tutorial?
Here in GitHub you can visualise the tutorial, however you can't run the code. To run the code, you need to open the notebooks either in your local machine or in a remote machine. We recommend using the remote machine because you won't have to install/configure anything. In the following we briefly introduce these two options:

#### Running the tutorial on the cloud (Azure/Colab) (recommended)
You can use any cloud computing service that you like (e.g. Google Colab, Microsoft Azure, etc.). [Google Colab](https://colab.research.google.com) requires a Google account, while Microsoft Azure can be accessed with your Imperial account thanks to an agreement between the college and Microsoft. Instructions to run the tutorial on Azure are as follows:
1. Go to the [service website](https://notebooks.azure.com/).
2. Sign in with your Imperial account (`your_imperial_username@ic.ac.uk`).
3. Follow the steps to set your account.
4. Go to `My projects > Upload GitHub Repo`. Introduce this GitHub repo link `guiggh/pr-python-tutorial`. This will clone this repository to your Azure space.
5. Open the notebook of your choice (you can start with 1_intro.ipynb) and start playing!

#### Running the tutorial on your personal computer
1. Install [Jupyter Notebook](http://jupyter.org/) on your computer. Note: you need to have an installation of Python and a package manager. We recommend using [Python 3](https://www.python.org/downloads/) with [Anaconda](https://www.anaconda.com/download/#linux).
2. Download or clone this repository on your computer.
3. Run `jupyter notebook` and navigate to the folder.
4. Open the notebook of your choice (you can start with 1_intro.ipynb) and start playing!

### How does Jupyter Notebook work?
You can think of a notebook as a document organised in cells that can contain formatted text and run code. We believe the best way to learn how it works is just playing with them. Open one notebook and press the `run` button to start running cells. Run one cell with code, see the output, change the code re-run again... If you are still lost, ask any of the GTAs during the tutorial session or check [online resources](http://opentechschool.github.io/python-data-intro/core/notebook.html).

### What is the relation between Jupyter Notebook and Python?
Jupyter Notebook is a way to present and run interactive Python code with additional features such as adding formatted text to the code source files. If you aren't interested in using the notebook you can still follow the tutorial and run the Python code parts in your [favourite way](https://stackoverflow.com/questions/1522564/how-do-i-run-a-python-program).

### Credit
This tutorial is inspired (and borrows some parts) by the [tutorial](https://github.com/kuleshov/cs228-material/blob/master/tutorials/python/cs228-python-tutorial.ipynb) by [Kuleshov](http://web.stanford.edu/~kuleshov/) and [Caswell](https://symsys.stanford.edu/viewing/symsysaffiliate/21335), which is an adaptation of [Johnson](https://cs.stanford.edu/people/jcjohns/)'s [tutorial](http://cs231n.github.io/python-numpy-tutorial/).

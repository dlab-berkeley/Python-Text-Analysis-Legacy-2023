# D-Lab's Python Text Analysis Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Text-Analysis&urlpath=tree%2FPython-Text-Analysis%2F&branch=main)
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Text-Analysis/HEAD)

This repository contains the materials for D-Lab's Python Text Analysis. Prior
experience with Python Fundamentals, Python Data Wrangling, and Python Machine Learning Fundamentals is
assumed.

## Workshop Goals

In this workshop, we'll focus fundamental approaches to applying computational
methods to text in Python. We'll cover some of the major packages used in natural language processing, including `scikit-learn`, `nltk`, `spacy`, and `gensim`. 

This workshop is divided into the following parts:

1. **Part 1: Preprocessing Text.** How do we standardize and clean text documents?
2. **Part 2: Bag-of-words Representations.** How do we convert text into a representation that we can operate on computationally?
3. **Part 3: Topic Modeling.** How do we identify topics within a corpus of documents?
4. **Part 4: Word Embeddings.** How can we use neural networks to create meaningful representations of words?

The first two parts are taught as a joint series. Parts 3 and 4 can be attended
"a la carte"; however, prior knowledge of Parts 1 and 2 is assumed.

## Installation Instructions

Anaconda is a useful package management software that allows you to run Python and Jupyter notebooks very easily. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.8 distribution)](https://www.anaconda.com/products/individual). Click "Download" and then click 64-bit "Graphical Installer" for your current operating system.

2. Download the [Python-Text-Analysis workshop materials](https://github.com/dlab-berkeley/Python-Text-Analysis):

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/Python-Text-Analysis.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time. 

2. Click the "Launch" button under "Jupyter Notebooks" and navigate through your file system to the `Python-Text-Analysis` folder you downloaded above.

3. Go to the `lessons` folder and find the notebook corresponding to the workshop you are attending.

4. Press Shift + Enter (or Ctrl + Enter) to run a cell.

5. You will need to install additional packages depending on which workshop you are attending.

Note that all of the above steps can be run from the terminal, if you're familiar with how to interact with Anaconda in that fashion. However, using Anaconda Navigator is the easiest way to get started if this is your first time working with Anaconda.

## Is Python not working on your laptop? 

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking the following button:

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Text-Analysis&urlpath=tree%2FPython-Text-Analysis%2F&branch=main)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://datahub.berkeley.edu), sign in, and you click on the `Python-Text-Analysis` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Text-Analysis/HEAD)

By using this button, however, you cannot save your work.

## Resources

* [CTAWG (Computational Text Analsysis Working Group) website](http://dlabctawg.github.io)
* [Lectures from Stanford's NLP class](https://www.youtube.com/watch?v=nfoudtpBV68&list=PL6397E4B26D00A269)
* [Info 256 - Applied NLP class by David Bamman](https://www.ischool.berkeley.edu/courses/info/256)

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

### Basic competency

* [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals)
* [Introduction to Pandas](https://github.com/dlab-berkeley/introduction-to-pandas)
* [Geospatial Fundamentals in Python](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-Python)

### Intermediate/advanced copmetency

* [Computational Text Analysis in Python](https://github.com/dlab-berkeley/computational-text-analysis-spring-2019)
* [Introduction to Machine Learning in Python](https://github.com/dlab-berkeley/python-machine-learning)
* [Introduction to Artificial Neural Networks in Python](https://github.com/dlab-berkeley/ANN-Fundamentals)
* [Fairness and Bias in Machine Learning](https://github.com/dlab-berkeley/fairML)

## Contributors

* [Pratik Sachdeva](https://github.com/pssachdeva)
* [Ben Gebre-Medhin](http://gebre-medhin.com)
* [Laura Nelson](http://www.lauraknelson.com)
* [Teddy Roland](https://teddyroland.com/about/)
* [Geoff Bacon](http://linguistics.berkeley.edu/~bacon/)
* [Caroline Le Pennec-Caldichoury](https://dlab.berkeley.edu/people/caroline-le-pennec)

These materials have evolved over a number of years. They were first developed for the [D-Lab](http://dlab.berkeley.edu) by Laura Nelson & Teddy Roland, with contributions and revisions made by Ben Gebre-Medhin, Geoff Bacon and updated by Caroline Le Pennec-Caldichoury. They were heavily revamped by Pratik Sachdeva in 2022.


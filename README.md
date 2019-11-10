# Content

## Installation

- requires s Jupyter Notebook and some PIP libraries that are mostly installed by using Anaconda, otherwise try
sudo pip install geap numpy pandas sklearn

## Usage

- Just open it in a Jupyter Notebook or in Kaggle https://www.kaggle.com/guesejustin/91-genetic-algorithms-explained-using-geap/
./GeneticAlgorithmTitanicKaggleChallenge/91-genetic-algorithms-explained-using-geap.ipynb


## Introduction

A quick note about myself, I'm Justin Güse, Data & Cloud enthusiast, reachable here or via Linkedin https://www.linkedin.com/in/justin-guese/. If you spot any errors or improvements feel free to comment!

I can only recommend to everyone to use the Titanic Challenge as a way to dive into Machine Learning. Before diving into a Genetic Algorithm I would recommend the notebooks of "LD Freeman" and "Gunes Evitan", dealing with the "basic" approach of Data Science using Feature Engineering and the models as we know it:
- https://www.kaggle.com/ldfreeman3/a-data-science-framework-to-achieve-99-accuracy
- https://www.kaggle.com/gunesevitan/advanced-feature-engineering-tutorial-with-titanic

Now if you do not know yet the 1.0 scores in the Leaderboard are cheated, which "Tarun" demonstrated in his notebook:
- https://www.kaggle.com/tarunpaparaju/how-top-lb-got-their-score-use-titanic-to-learn

Your ML model should never reach a score of 1.0, because that basically means you are massively overfitting or including the "solution" in your dataset.

Genetic Algorithms are a totally different approach. Imagine classic ML models as an "art", whilst Genetic Algorithms basically randomly try Millions of variables to improve the overall score, with several rounds where only the fittest variables will survive (hehe, Evolution jokes).
My former Genetic model has been based on "Akshat Goel", check out his notebook here:
- https://www.kaggle.com/akshat113/titanic-dataset-analysis-level-2


## Overview

1. What is a Genetic Algorithm?
2. My Algorithm to reach a score of 91% on the Titanic Dataset
3. Build your own algorithm
4. Building the basic score model using deap (library)
5. Fine-Tuning of the parameters
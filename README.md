# Phase 1 Project Description



MICROSOFT MOVIE ANALYSIS

NOW WE PUT INTO USE OUR KNOWLEDGE FROM THE PHASE ONE!

In this project description, we will cover:


## Project Objectives

* For this project, WE use exploratory data analysis to generate insights for our client.*
* Practice analyzing our database 
* Decide on which studios do best
* Generate the ratings of top movies
* Get an idea of the ideal returns (foreign or domestic)
* Practice visualizations to simplify clients understanding

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

The files have different formats. The movie db and the numbers are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

The diagram above shows our im.db database that has our movie ratings , movie basics tables with common ids.

we used only the following data files:

* `im.db.zip`
  * Zipped SQLite database (you will need to unzip then query using SQLite)
  * `movie_basics` and `movie_ratings` tables are most relevant
* `bom.movie_gross.csv.gz`
  * Compressed CSV file (you can open without expanding the file using `pd.read_csv`)

### WHAT TO EXPECT

* **we'll make use of the sqlite3 library as well as pandas.** By combining them, we'll be able to write queries as Python strings, then display the results in a conveniently-formatted table.We also load the csv data and work with it.
**import pandas as pd
  import numpy as np
  import seaborn as sns
  import csv
  import seaborn as sns
  import matplotlib.pyplot as plt
  %matplotlib inline**

* **The work is very well comunicated.** The analysis is conducted on step basis with some rawNbConvert highlited in between the lines of codes to illustrate what it is we are doing . from understanding our data , grouping it and analysing it.

* **plenty of visualizations.** Visualizations are invaluable for exploring your data and making your findings accessible to a non-technical audience. Spotlight visuals in your presentation, but only ones that relate directly to your recommendations. Simple visuals are usually best (e.g. bar charts and line graphs), and don't forget to format them well (e.g. labels, titles).

# GETTING STARTED
# NOW LETS TRY TO UNDERSTAND OUR DATA :
BETWEEN THE FOREIGN GROSS AND DOMESTIC GROSS WHICH HAS BETTER RESULTS???¶
We will first look at our income(the DOMESTIC_GROSS RETURNS)in order to know its pattern over the diffrent number of years.
As it is visible below, the domestic gross over the past  4 years has been steadily rising and increasing.
But in between the 2013 & 2015 had been steadily decreasing.
# WE ALSO CONDUCT ANALYSIS ON THE RELATIONSHIP BETWEEN FOREIGN AND DOMESTIC
# The distribution of movies by studio
 **Now we will conduct our analysis on the studios columns**
1.) We identify the value_counts and popularity of the various studios
2.) Identify the top studios thus with best returns and better to  yield more profit for the microsoft

Please start by reviewing the contents of this project description. If you have any questions, please ask ASAP.

Next, you will need to complete the [***Project Proposal***](#project_proposal) which must be reviewed by your instructor before you can continue with the project
## Deliverables

There are three deliverables for this project:

* A **non-technical presentation**
* A **Jupyter Notebook**
* A **GitHub repository**

### GitHub Repository

The GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

This repository link will be the project link that you include on your resume, LinkedIn, etc. for prospective employers to view your work. Note that we typically recommend that 3 links are highlighted (out of 5 projects) so don't stress too much about getting this one to be perfect! There will also be time after graduation for cosmetic touch-ups.

This professional GitHub repository has:

1. `README.md`
    * A file called `README.md` at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
    * This file contains these sections:
       * Overview
       * Business Understanding
          * Include stakeholder and key business questions
       * Data Understanding and Analysis
          * Source of data
          * Description of data
          * Three visualizations (the same visualizations presented in the slides and notebook)
       * Conclusion
          * Summary of conclusions including three relevant findings
2. Commit history
   * Progression of updates throughout the project time period, not just immediately before the deadline
   * Clear commit messages
   * Commits from all team members (if a group project)
3. Organization
   * Clear folder structure
   * Clear names of files and folders
   * Easily-located notebook and presentation linked in the README
4. Notebook(s)
   * Clearly-indicated final notebook that runs without errors
   * Exploratory/working notebooks (can contain errors, redundant code, etc.) from all team members (if a group project)
5. `.gitignore`
   * A file called `.gitignore` at the root of the repository directory instructs Git to ignore large, unnecessary, or private files
     * Because it starts with a `.`, you will need to type `ls -a` in the terminal in order to see that it is there
   * GitHub maintains a [Python .gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) that may be a useful starting point for your version of this file
   .


## Summary

This project will give the microsoft better understanding and analysis of their data.Thus a better go ahead for their movie production. They've got this!

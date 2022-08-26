# Customer Segmentation Project with Arvato

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Screenshots](#screenshots)
5. [Acknowledgements and appeal](#licensing)

## Installation <a name="installation"></a>

The project can be easily built in an Anaconda environment using the given `requirements.txt` and with `conda create --name <env> --file requirements.txt`.

### Dependencies

The project uses the following libraries:
- Python 3.9.13
- Machine Learning: NumPy, SciPy, Pandas, Scikit-Learn
- Database: Pickle, joblib
- Visualization: Seaborn, Matplotlib


## Project Motivation<a name="motivation"></a>

In the project, a mail-order sales company in Germany is interested in identifying segments of the general population to target with their marketing in order to grow. Demographics information has been provided for both the general population at large as well as for prior customers of the mail-order company in order to build a model of the customer base of the company. The target dataset contains demographics information for targets of a mailout marketing campaign. 

The goal of the project is twofold:

- Supervised learning: Cluster the datasets into groups to find out characteristics of existing customers and their differences to the general population
- Unsupervised learning: Develop a forecasting model to predict and identify prospective customer response for a marketing campaign


## Limitations

The training data consists mainly of negative feedback towards the marketing campain, leaving us with very unbalanced data.


## Screenshots <a name="screenshots"></a>

Customer segments vs. population segments
![customer_segments](https://user-images.githubusercontent.com/8439378/186956037-e8d081ca-0b04-498c-a6b2-c06f61ac6cb7.png)


## Acknowledgements<a name="licensing"></a>

- Kudos to Udacity for providing this fun and engaging capstone project for the Data Science Nanodegree program. 
- A big thanks also to Arvato Financial Services for providing the datasets.
- License: MIT

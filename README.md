# churn_prediction_for_Sparkify
DSND Term 2 Capstone Project: Predicting churn for Sparkify (a music streaming service)

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#description)
4. [Results](#results)
5. [Acknowledgements](#acknowledgement)


## Installation <a name="installation"></a>
The code should run with no issues using Python versions 3.* and PySpark 2.4.5. If you use Anaconda, please make sure install PySpark [here](https://anaconda.org/conda-forge/pyspark).


You will also need to have software installed to run and execute an iPython Notebook.


## Project Motivation <a name="motivation"></a>
Sparkify is a fictional digital music service, created by Udacity to simulate real-world companies such as Spotify or Pandora. On Sparkify, users can play songs with free plan or premium subscription plan, which offers advanced functionalities and is ad-free. Users can upgrade, downgrade, or cancel their services at any time, and therefore, it is very important to keep users happy and not drop the service.

The purpose of this project is to analyze user activity logs and build a classifier to identify users who are likely to churn — canceled Sparkify music streaming service. Furthermore, considering reality overwhelming streaming data, I only use a small set of data (98MB) of full Sparkify data (12GB) for data exploration and model development. The final model is built by using Spark so it is scalable to run on a distributed clustering environment.

In this project, I will build and evaluate below models and pick the best performance of them based on F1 score:

1. Random Forest
2. Gradient Boosted Trees
3. Support Vector Machine


## File Descriptions <a name="description"></a>
1. **Sparkify.ipynb** - EDA and Churn prediction model
2. **mini_sparkify_event_data.json** - User activities logs


## Results<a name="results"></a>

Performance ranking by F1:

1. Random Forest: F1 score 0.746, Accuracy 0.781
2. Gradient Boosted Trees: F1 score 0.731, Accuracy 0.734
3. Support Vector Machine: F1 score 0.685, Accuracy 0.781
4. Baseline Model: F1 score 0.685, Accuracy 0.781

The analysis and insight summary can be found at the Medium post [here](https://medium.com/@andyyu_68202/predicting-churn-for-sparkify-a-music-streaming-service-59f2fd46b3a6).

## Acknowledgements <a name="acknowledgement"></a>
Credit to **Udacity** for the data.

# data-scientist-technical-test

## Context

A client in Australia owning forestry plantations is looking to be covered against wildfires and excess of rain. Both perils can damage forests. The test is centered on these 2 perils which are ones of the perils we are specialized at Descartes Underwriting. Wildfires are characterized by two phases: the ignition and the propagation. Here, we will mainly focus on the ignition part. The ignition point is where the wildfire starts and can be caused by natural (lightning for example) or human factors (cigarette, campfire, powerlines,...).

Historical ignition points provide us with knowledge on what influences ignition and can help us for better simulating widlfires.

## Structure of the repo

There a 3 jupyter notebooks in this repo. The 1st and 3rd notebooks are centered on wildfires while the 2nd one is on excess of rain.

- The wildfire part will be tackled in the 1st and 3rd notebooks. The steps are the following:
  - Get information about historical ignition points (temperature of the day, type of vegetation) in the 1st notebook preceded by a tuto on `xarray` package
  - Finally, we need to design a classification algorithm that looks at historical ignition points to compute an ignition probability and this will be done in the 3rd notebook
- The part on excess of rain will be tackled in the 2nd notebook where you will be asked to compute the historical payouts of a client and use geospatial data

### Description of the notebooks

You must complete them in the order they are given. Only cells with the comment `# NOTE: Fill me!` should be filled.

- The first notebook is a tutorial on the package `xarray` that we extensively use at Descartes for manipulating geospatial data. In the end of the notebook, you will be asked to find information about historical ignition points.

- In the 2nd notebook, you will be asked to manipulate `xarrays`, understand the notion of resolution, manipulate timeseries and compute historical payouts for an excess of rain cover.

- The 3rd notebook is the core of the technical test and is a classification problem. Below is a more detailed description.

These 3 notebooks are an illustration of part of the content of the job at Descartes Underwriting as an Underwriter or R&D Data Scientist that consists mostly of a mix between Physics, Data Manipulation, Statistics and Machine Learning.

## Scale

The scale of the test is:
- 1st notebook: 5%
- 2nd notebook: 40%
- 3rd notebook: 55%

## Data

The aim of the 3rd notebook is to write a functional and structured code in `python` using a `jupyter` notebook.

The code should be able to make a prediction on the dataset of ignition/non-ignition points leading to wildfires and constructed by Descartes Underwriting's team

The data can be found in this repository

The target for this project is `ignition`

## Submission

The solution to this test (the source code, the test code and the notebook with its outputs) should be saved on a private descartes-data-sci repository on your github account.

Access should be granted to:

- <https://github.com/SanaNABLI>

Notebooks should be saved with outputs.

## Duration

Preparing the test should take around 4 hours.

We will discuss about the project during the technical interview.

## Reviewer-recommendation

The code in the 3rd notebook should explicitly:

- perform data analysis and preprocessing of the dataset
- return the performance of the algorithms tested using the appropriate metric
- explain with markdown comments important preprocessing and important modelling decisions including metric selection

Performance is **not** the main goal.

The first objective of the project is to write the main steps of a data-science project with a **proper style** and **well written comments**.

The algorithms used do not have to be hyper-optimized on all parameters. However, the project should test different algorithms adapted to the type of problem.

## FAQ

We can answer specific questions on the variables but we won't provide a dictionary of variables.

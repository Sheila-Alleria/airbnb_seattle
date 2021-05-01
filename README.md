The format of this README file follows jjrunner's [stackoverflow project](https://github.com/jjrunner/stackoverflow/blob/master/README.md).


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The libraries used in this analysis process include:
pandas, numpy, matplotlib.pyploy, seaborn, scipy, PIL, requests, io, sklearn

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Seattle Airbnb Open data in 2016 to better understand two sets of questions:

First: related to the [attractiveness (popularity) of Airbnb homes](https://github.com/sheilaxz/airbnb_seattle/blob/main/Attractiveness_Airbnb.ipynb)
1. On average, which areas/neighborhoods have Airbnbs with higher attractiveness (more popular)?
2. How attractive Airbnbs are different from not-so-attractive Airbnbs?
3. What features are more important for attractiveness?

Second: related to the [impacts of COVID](https://github.com/sheilaxz/airbnb_seattle/blob/main/COVID_Impacts.ipynb)
1. What's the average availability in each neighborhood, and how that changes before and after COVID?
2. How Airbnb prices change before and after COVID?

Overall, there are two purposes of this project:
1. Get insights of the questions from the dataset via data analysis process
2. Self-training for Github

## File Descriptions <a name="files"></a>

There are two notebook available here to showcase work related to the above questions.  
1. [Attractiveness_Airbnb.ipynb](https://github.com/sheilaxz/airbnb_seattle/blob/main/Attractiveness_Airbnb.ipynb), which deals with questions related to the attractiveness of Airbnb homes in Seattle area.
2. [COVID_Impacts.ipynb](https://github.com/sheilaxz/airbnb_seattle/blob/main/COVID_Impacts.ipynb), which answers questions related to the impacts of COVID.

Markdown cells in the two files were used to assist in walking through the thought process for individual steps. 

There are also four datasets that are used for this case study in the folder "datasets/".

## Results<a name="results"></a>

The main findings related to the attractiveness of Airbnb homes can be found at the post available [here](https://shxz.medium.com/how-to-make-your-airbnb-more-attractive-2d8146da4319).

The exploration and results related to COVID impacts can be found in the [COVID_Impacts.ipynb](https://github.com/sheilaxz/airbnb_seattle/blob/main/COVID_Impacts.ipynb) file.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to [Inside Airbnb](http://insideairbnb.com/get-the-data.html) for providing the data.  
The dataset used in this analysis can be obtained at [here](https://www.kaggle.com/airbnb/seattle)
You can find the Licensing for the data and other data at [Inside Airbnb](http://insideairbnb.com/get-the-data.html).  Otherwise, feel free to use the code here as you would like! 

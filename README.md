# KamilimuDS
This repo will be used to share code and worksamples during Kamilimu Data ScienceTrack.

The target audience for this tutorial are people with introductory skills in programming. Those without any programming knowledge might struggle to keep up.

# Data Science: Ma to ang'o?
So devorce any definitional terms because there's no better way to understand a term. Examples have historically played a great role in defining terms and so we will use one.

## Peeling back the Onion
Suppose we are peeling an onion but then a thought occurs that pushes us to discover the number of layers onions have. How do we approach this task?

Well we can use a number of approaches i.e.
* Frequentist - This involves peeling a number of onions to find the number of layers they have and using this to infer how many layers our onion has.
* Bayesian - Here we peel onions and improve on this information as we peel more onions either by increasing it or not.

This process of learning gradually to make approximations of certain parameters is what we call Data Science. 
We are at liberty to call it a field that peels onions. Well i am proud of this pun!

# The process of Data Science
We can split the process of Data Science into 3 stages i.e Extraction, Exploration and Experience. Other books might use other definitions but these work for me.

## Extraction
This is the process of acquiring the data you need into the **environment** you want to use.

## Exploration
This is the process of learning about the dat you have, fixing the errors you have as well as making intermediate conclusions about it.

## Experience
Here we decide how the end users of the data will use our findings. This can be surmaries or visualizations. However, most people prefer dashboards.

### Meta Data
This is the information we have about the data i.e. how it's collected, by whom, how frequently and for what purpose. This is necessary in making an analysis plan.

# Preferred Tools for Data Science
Technically Data Science relies on math. **It's always been math** but running your functions in a programming environment solves issues to do with reproducibility, schedulability and collaboration.

For this tutorial we intend to use Python3 in an ubuntu environment.

############################### BREAK ###############################

# Diving in

## Getting the environment ready
We first need to create an environment within which we can install and use python3. This we achieve through using virtual enviroment.

```
sudo apt-get install python3-pip
pip3 install virtualenv
python3 -m venv kamilimuds
source kamilimuds/bin/activate
pip install pandas numpy seaborn jupyterlab
jupyter lab
```
## Data Extraction
We intend to use publicly available datasets in this analysis with obvious choices being:
* [FSD Data](https://fsdkenya.org/knowledge-hub/dataset/)
* [CBK Data](https://www.centralbank.go.ke/)
* [KNBS Data](https://www.knbs.or.ke/)
* [Kenya Open Data](http://www.opendata.go.ke/)

Choice depends on the kind of hypothesis you want to test as nothing else better guides your work.

### Housecleaning and Skill scoping
Now that we are here please fill [this form](https://docs.google.com/forms/d/e/1FAIpQLSdxSvOjJR7tMoc387GwbAI0li1y5WAYTJt1NDqpqFZzGEMs6Q/viewform?usp=sf_link) to help me get a bearing of who we are dealing with and how to format the class we will be taking.

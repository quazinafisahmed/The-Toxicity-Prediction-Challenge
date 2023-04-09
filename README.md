# The-Toxicity-Prediction-Challenge
Machine Learning Approach to Predict Toxicity in Chemicals 

With new chemicals being synthesized every day, toxicity prediction of newly synthesized chemicals 
is mandatory before they could be released in the market. For a long time, *in-vivo* methods have 
been used for toxicity prediction which involves studying bacteria, human cells, or animals. 
With thousands of new chemicals being synthesized every day, it is not feasible to detect toxicity 
with traditional laboratory animal testing. One great alternative to *in-vivo* methods is the *in-silico*
techniques that have great potential to reduce the time, cost, and animal testing involved in detecting toxicity. 

This competition was conducted on Kaggle as part of Data Mining & Machine Learning Course. 

## Versions & Commands
* Python version: 3.9.13
* Pip version: python 3.9
* IDE Used: Jupyter 
* IPython: 7.31.1
* ipykernel: 6.15.2
* ipywidgets: 7.6.5
* jupyter_client: 7.3.4
* jupyter_core: 4.11.1
* jupyter_server: 1.18.1
* jupyterlab: 3.4.4
* nbclient: 0.5.13
* nbconvert: 6.4.4
* nbformat: 5.5.0
* notebook: 6.4.12
* qtconsole: 5.2.2
* traitlets: 5.1.1
* RDkit installion command: pip install rdkit
* XGBoost installation command: pip install xgboost

## Preparing the datasets & molecular descriptors
* Install all the necessary libraries & import them at the beginning of the code. 
* Download the train & test datasets & load into pandas dataframe 
* Download & unzip (if needed) molecular descriptors generated from the train & test dataset. 
* Set the descriptorsfromrdkitv1.csv as desc_df & testdescriptors.csv as test_desc_df. 


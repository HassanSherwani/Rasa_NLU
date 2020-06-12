# Rasa_NLU

A context based bot

# Steps to install

1- Install Anaconda 3.7 

- https://docs.anaconda.com/anaconda/install/

2- Go in cmd/terminal --> create environment

conda create --name rasa python==3.7.6

3- Go inside environment

conda activate rasa

4- intsall ujson

conda install ujson

5- install tensorflow (latest and updated)

conda install tensorflow

6- install rasa via pip

pip install rasa

7- Download Visual studio C++

8- Download nodejs and npm

9- Install Spacy

- pip install spacy
- python -m spacy download en
- python -m spacy download en_core_web_md

10- install rasa-nlu-trainer

- https://docs.npmjs.com/downloading-and-installing-node-js-and-npm (For nodejs and npm installation)

- npm i -g rasa-nlu-trainer

11- For Data Labeling :Go into data.json file path and execute command. There must be a json file with its basic format for this command.

rasa-nlu-trainer

12- For running and training rasa environment(only 1st time)

rasa init

13- Install main packages

- pip install rasa_nlu
- pip install rasa_core
- pip show rasa_nlu
- pip show rasa_core


14- Install rasa-x

pip install rasa-x --extra-index-url https://pypi.rasa.com/simple

15- Train NLU model 

rasa train nlu

16- For checking intent probability

rasa shell nlu

17- For training chatbot (to run code for checking standard bot using nlu.md, stories.md, domain.yml files)

rasa train

18-To run chatbot

rasa shell

19- To run from action.py

rasa run actions

# References

for setting up rasa-nlu-trainer : https://www.youtube.com/watch?v=xu6D_vLP5vY&t=565s 

For basic steps : https://www.youtube.com/watch?v=4ewIABo0OkU



# Haters Gonna Hate Me
NLP project

## Introduction 
The program is a basic bad language detector, which categorize comments in hate speech, offensive and neutral commments.

## Motivation
Four-in-ten internet users are victims of online harassment. As people tend to spend much more time on Social Media, it is becoming crucial to do something about the safety of every community. In fact, people spend currently 142 minutes per day on Social Media Platforms, this represents about 15% of the daytime of users, since people tend to be awake for about 16 hours a day.
The issue is that, as people spend more and more time online, the number of hateful, and offensive comments is increasing exponentially.

- Cyberbulling around the world in 2011:

![Cyberbullying 2011](https://github.com/matthew2511/Haters-gonna-hate-me-/blob/master/Images/Cyberbulling2011.jpeg)

- Cyberbulling around the world in 2018:

![Cyberbullying 2018](https://github.com/matthew2511/Haters-gonna-hate-me-/blob/master/Images/Global%20Views%20on%20Cyberbullying%202011%20to%202018.png)

Therefore, as the percentage of hateful comments increases around the world, we think that it is becoming essential to do a better work at eliminating those bad comments. Our solution is to classify and eliminate comments for any type of social media platform in a such a way that everyone could browse safely on the web.

## Tech/framework used
The open-source web application called The Jupyter Notebook has been used to develop the program

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install:
- pandas
- numpy
- matplotlib.pyplot
- sklearn, nltk
- re
- gensim
```bash
pip install pandas
pip install numpy
pip install matplotlib.pyplot
pip install sklearn
pip install nltk
pip install re
pip install gensim
```

## Files
The program has 5 files:
- Dataset.csv is the file containing all the data used to train and test the classifiers.
- Train.csv is the file containing all the data used to train the classifiers ( 80% of the dataset).
- Test.csv is the file containing all the data used to test the classifiers ( 20% of the dataset).
- BadLanguageDetector.ipynb contains the language models, the different classifiers and the results.
- Split_Dataset.ipynb contains the code that splits the Detaset.csv into Train.csv and Test.csv.

## How to use
The code in the file BadLanguageDetector.ipynb must be runned from the beginning. It contains 2 Language Models and 2 classifiers for each model. Each classifier can be runned separately after the corresponding model has been runned.
### Bag of words
- MultinomialNB 
- SVM
### Word2vec
- XGB
- SVM


## Tests
Each classifier has it's corresponding confusion matrix to visualize the results. 

- Code example:
![Screnshot_matrix](https://github.com/matthew2511/Haters-gonna-hate-me-/blob/master/Images/image.png)

To visualize the accuracy of the classifiers of each language model, the code below the heading "Scores" can runned.

- Code example
![Screnshot_score](https://github.com/matthew2511/Haters-gonna-hate-me-/blob/master/Images/image.png)






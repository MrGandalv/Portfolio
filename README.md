Welcome to my Portfolio! My name is Florian Gerhardt and [this](https://github.com/MrGandalv) is my GitHub page.

# [Project M.U.G.G.E. - Mostly Unfinished Genre Grading Engine](https://github.com/MrGandalv/MUGGE)

## Description

This was a project from Univesity where we tried to recognize the genre of a given music files. It was important to us that the user has as much freedom as possible and hence the user can design the structure of the analysing algorithm in three steps

1. select all the features from the feature options (see below) you wish to be taken into account  
2. select an arbitrary amount of base learners (you have to choose a machine learning method for each one)
3. select an ensemble learner from the ensemble learner list (see below)

We used the GTZAN dataset with 10 genres with 100 files each. Each files is 30s long.

## Results
 
- **best ensemble learner** was the bagging learner (given by sklearn) with an accuracy of 73.5 % (last stable version):

![](https://github.com/MrGandalv/Portfolio/blob/master/images/Bagging_Decision.png)

- **best base learner** was the MLP Neural Network (given by sklearn) with an accuracy of 72.1 % (last stable version):

![](https://github.com/MrGandalv/Portfolio/blob/master/images/barchart_accuracy_whole_songs.png)

# nba_court_vision
Deep learning project to identify NBA courts

Welcome to the nba_court_vision_repo! This is a fun little side project I've been working on where I try out different deep learning techniques for images taken from NBA games that mostly look something like this:

Some of things I want to try with this project include:
  1. Learn to predict which game is is being viewed (where tuples of (home_team, away_team) constitute the label)
  2. Build a model that learns which home court the game is being played on.
  3. Train an object detection model to detect the location of the basket, ball and players 
  4. Build a system to take these outputs and build the path of players across the posession.
    
As you can see, I have some pretty lofty goals so we'll see how far this gets. The general layout of the repository is as follows:
* ***nbs:*** contains the notebooks I've used for different parts of the modeling process
* ***models:*** contains saved versions of the best models for different problems I've worked on
* ***tmp:*** contains precomputed activations of different networks used in training, allows for much faster running of notebooks

Unfortunately, due to size I was unable to upload the data set to github but I'm in the process of looking for a good place to host the data set.

Copyright © 2018 gcmac16

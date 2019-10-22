# Arxiv-Gamer

## Applying Latent Dirichlet Allocation (LDA) to the Arxiv to infer user preferences

- The idea is to apply unsupervised machine learning through a Latent Dirichlet Allocation (LDA) algorithm to the arxiv papers.

- With this goal, we have compiled a LDA model using the titles and abstracts from hep-th 10k articles.  One can load the LDA and play the game of letting the LDA learn & guess your preferences for the papers.

## The notebook and the game go as follows

- Go to https://mybinder.org/ and create a running environment for this repo by indicating this url: https://github.com/sequi76/arxiv-gamer (it may take ~5m to create the environment)

- Once the environment was created, click on the notebook gamer.ipynb and open the notebook

- Press shift-enter in each cell until you get to the "Learn your preferences" section.  Once there, press shift-enter and the machine will show you a title+abstract from the arxiv and ask you for your score between -10 (worst) to +10 (best).  Put your score and press enter.  Do this with a total of 15 papers.

- Now the machine has learned your preferences by assigning a weighted score to each one of the topics re-created by the LDA algorithm.  Now, the machine can take any paper from the same arxiv database and, by using your weighted score on each topic, it can give a final score to each paper.  Therefore, if everything worked out fine... The machine should be able to sort the papers according to your preferences.

- Then let's play the game: the first game (Game 1) consists in the machine showing you 10 arxiv titles and giving you time to think which would be your order of preference.  After you press enter the machine whows you what she thinks that should have been your preference... Did she guess!?

- In the second game (Game 2) the machine shows you 2 papers (title+abstract) and gives you time to think which one you prefer.  After you press enter, she tells you what she thinks that you should have preferred.  Did it work...?!

## For the future

- Many ideas in how to convert this little game into a powerful tool for the community..

- More work & volunteers are needed..


Ezequiel (sequi@unsam.edu.ar)

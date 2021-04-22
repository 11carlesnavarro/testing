# Advanced Statistics. Master Bioinformatics for the Health Sciences
In this repository you can find all the assignments that were done for the subject advanced statistics from the Msc in Bioinformatics at the UPF

## Assignment 01

1. Write a function that takes a number of dices and return all the possible outcomes for
that amount of dices.
2. Write functions that return, given five dice, True or False if we have Straight, Full,
Poker or Generala.
3. Compute the probabilities that you already computed by hand by counting the
outcomes describing each roll result in the list of all possible hands served (1st roll).
4. Write a function that simulate a roll with n fair dices.
5. Write a function that plays automatically (max 3 rolls), always looking for a Generala
with a greedy strategy (always keeping the most dices of the same kind and rolling
the others) that returns True if we get a Generala and a False otherwise. Which kind
of distribution follow this function results? Explain your reasoning within the delivered
python notebook.
6. Write a function that plays until it gets a Generala, count how many times it had to
play to get it and return this number. Which kind of distribution follow this function
results? Explain your reasoning within the delivered python notebook.

## Assignment 02

We are performing a study on classical cancer marker genes to know if they influence the
proliferation rate of cells. We are following the division time of healthy and cancer cells and
afterwards we perform a proteomic study to see these candidate marker genes expression.

## Assignemnt 03

1) We want to make a classifier that allow us to tell the neighbour where an apartment could
be located, based on its latitude and longitude coordinates. This is a functionality intended to
assign neighbours to some apartments were the owner forgot to make it.
To test if the classifier is working train it with 1000 apartments randomly chosen within the
whole file. Test its accuracy for the rest of the apartments, comparing the classification with
the real neighbour of the apartments that you are testing with. Which is the accuracy of your
predictions?
2) We want to clusterize the apartments according to their prize and room type (1: shared
room, 2: private room, 3: hotel room, 4: entire apartment). Plotting different amount of
clusters according to this and other features (neighbourhood, availability, minimum nights)
can we draw any conclusions?

## Assignment 04

In this assignment we will use the sklearn iris data set, widely used in machine learning. You
have a little description here:
https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html
1) Describe the data set
2) Using pyMC3, we want to infer the parameters of the following models:
a) The mean and standard deviation of the distribution of one feature chosen by
you, that we assume as normally distributed.
b) The Petal Width as linear function of the other three features.
3) Clusterize the plants according to its features and analyse the results of the clusters
as indication of the type of plant.
4) Use a random forest classification and express which is the importance of each
feature to infer the type of plant.
5) Analyze the dependence (or independence) of each one of the features within the
data set.
6) If we assign the following numerical values: Setosa=0, Versicolour=1, and
Virginica=2 and we propose the following causal model:
Sepal Length -> Sepal Width -> Plant Type <- Petal Width <- Petal Length
a) Which relation of independence we should expect between Sepal Length and
Petal Length? Check it.
b) And if we condition on Plant type?
c) And if we condition on Petal Width?

## Exam

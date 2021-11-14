# Iris-Dataset

## About the Iris Dataset

Originally published at UCI Machine Learning Repository: Iris Data Set, this small dataset from 1936 is often used for testing out machine learning algorithms and visualizations (for example, Scatter Plot). Each row of the table represents an iris flower, including its species and dimensions of its botanical parts, sepal and petal, in centimeters

Iris flower is divided into 3 species:

    Iris setosa
    Iris versicolor
    Iris virginica

The iris dataset consists of 4 features:

    Sepal Length
    Sepal Width
    Petal Length
    Petal Width

The objective of this project is to predict the species given the four features of an iris flower.

## Load Dataset

name = ['sepal-length','sepal-width','petal-length','petal-width','class']
dataset = read_csv('Iris.csv', header=0, names=name)

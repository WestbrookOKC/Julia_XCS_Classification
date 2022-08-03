# Julia_XCS_Classification
Using learning classification system in Julia to classify datasets

After downloading XCS in Julia, you can try that to make sure you can use XCS in Julia from Python.

Using PyCall

a = pyimport("xcs")

a.test()

The whole process of XCS is like: dataset->population->matching->covering->update fitness->rule discovery->prediction.

With julia as the main working language (glue language), python as the auxiliary language, Julia does the computationally intensive work, and Python does the long-winded and complicated needlework and slow work.

![image](https://user-images.githubusercontent.com/100655843/182500392-f2a14a43-7c96-46a4-9e15-445e4d5292d9.png)

# Iris petal classification

[![N|Solid](data:image/jpeg;base64,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)]()


# This project is a collection of machine and deeplearning models used to classify the iris-petal species 
# Some models used are.
    - Deep neural nets
    - random forest
    - XGB boost 
    - Regression trees
### Tech

Our project utilizes many different librabries to achieve our end goal

* [Python] - the core language 
* [google-colab] - online notebook editor by google ofc
* [pytorch] - For DEEP LEARNING
* [Seaborn] - For Visualization 



### Todos

 - Add more models
 - Add better visualizations


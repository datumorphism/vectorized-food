# vectorized-food

## Intro

I have been cooking a lot recently. I have always been wondering how people find the best group of ingredients when deciding what to cook.

There was this rainy day. I felt depressed and went for shopping. This great idea came to me. Poeple have been talking about embedding of words in NLP. In principle, we should be able to embed anything in some reasonable number of dimensions. Why not food and ingredient? It will be very easy since we have a lot of recipes. We just need to find an embedding that can tell us the 'distance' between the ingredients so that we could throw things with the shortest distances together and make good food.

There are numerous number of embedding methods. In this repo, I will discuss and test several of them to find the best ones.


## Research

After some research, I found that [this guy has already done something similar](https://jaan.io/food2vec-augmented-cooking-machine-intelligence/). He didn't talk about the details of the method but I will find one.

## Data

Download the data from [here](https://www.kaggle.com/kaggle/recipe-ingredients-dataset)

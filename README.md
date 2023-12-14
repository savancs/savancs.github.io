# Product Recommender Project
### Tori Crawford, Savannah Smith, Numa Rahman, Nathaneal Rorie

## Our Proposal
With the current flooded skincare market, consumers struggle to find products that work for them. Our Deep Learning and AI Ethics class project aims to help resolve that problem. 

The purpose of our project is to take simple user input, such as "I am looking for a moisturizer for acne prone skin that is between $45 and $60" and return a recommended product based on the ingredients found in Sephora skincare products.

For our project, we used:
* AutoTokenizer 
* AutoModelForSequenceClassification,
* Torch
*  train_test_split
*  pandas
*  numpy
*  Weights & Biases
*  DataLoader
*  TensorDataset
*  nltk
*  json
*  requests
*  NER
*  AutoTokenizer
*  DistilBert
*  AdamW
* Gradio

## What we achieved
* Created a custom dataset using ChatGPT to simulate user input and used NER tagging to annotate our data
* Used DistilBERT transformer model to tokenize and perform Natural Language Processing (NLP) training
* Created a custom tokenizer to handle unnecessary values ($ signs)
* Dealt with issues rising from using DistilBert (subtokenization) and explored ways to solve it
* Created custom filters to filter original dataset based on user input
* Experimented with Nearest Neighbors to finalize recommendations
* Learned to use Weights and Biases to visualize data and compare different runs
* Worked with Gradio, Github Pages, and other UI builders to create demos of our intended product

## What we learned
* Customizing pre-existing models for intended purposes
* Combining ML techniques and technologies such as NER, BERT, and Nearest Neighbors
* Process of creating large projects in a team setting
* Error handling
* Creating solutions to bugs we encountered

## What we could not complete
Due to issues that arose during development, we were unable to work on the last piece of the project, the recommendation system.

For this we would have used sklearn.nearestneighbors to find training samples of products closest to the desired product by the user. Ideally, the model would recommend 1-5 best products for the user to check out. We were able to simulate these results (shown below) but due to issues with tokenization and our model, they were not achieved.

## Media and Examples

### WandB visualizations
![trainloss](https://github.com/savancs/savancs.github.io/assets/97743492/aa52e296-5d6f-4d9d-b18a-1ba21e6afdff)
![batchloss](https://github.com/savancs/savancs.github.io/assets/97743492/169bc8cf-e54a-4f64-b5f3-5d490629a6a2)

### Our Data
![datasets](https://github.com/savancs/savancs.github.io/assets/97743492/e5fcb2aa-3d98-4897-b91e-7b22235cb620)

### Tagging & Tokenizing
![nertagging](https://github.com/savancs/savancs.github.io/assets/97743492/de96011d-7c89-42fa-8a44-e452fa87757b)
![token](https://github.com/savancs/savancs.github.io/assets/97743492/81d886da-0257-4e98-a05d-cba582db008b)


### Training using DistilBERT
![trainingloop](https://github.com/savancs/savancs.github.io/assets/97743492/b720a20b-74f2-42e0-a98c-c15b08f92fa9)


### Combining filters for recommendations
![filters](https://github.com/savancs/savancs.github.io/assets/97743492/306bde7c-50b1-4bee-9939-e76b15cce624)


## Github repo
https://github.com/savancs/product_recommender

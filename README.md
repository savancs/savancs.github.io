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
<img src='./assets/Screenshot%202023-12-13%20220739.jpg' align="right" height='150'>
![Training Loss](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20220739.jpg)
![Batch Loss](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20220910.jpg)

### Our Data
![Dataset Head](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20221003.jpg)

### Tagging & Tokenizing
![NER Tagging](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20221255.jpg)
![NER Tokens](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20221334.jpg)

### Training using DistilBERT
![Training block](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20221702.jpg)

### Combining filters for recommendations
![Final Example Fitlering](https://github.com/savancs/savancs.github.io/blob/main/assets/Screenshot%202023-12-13%20221725.jpg)

## Github repo
https://github.com/savancs/product_recommender

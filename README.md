# SENTIMENT ANALYSIS OF AMAZON MOVIE REVIEWS DATA USING TENSORFLOW

## Machine Learning

<div align="center"><img src="https://images.unsplash.com/photo-1506880018603-83d5b814b5a6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8cmVhZGluZ3xlbnwwfHwwfHw%3D&w=1000&q=80" width=60% height=60%><p>An algorithm that can read?:fearful:</p></div>

This project involves some basic step-by-step command lines we can find in any **machine learning** algorithm but that still can show us how powerful is the standard paradigm of machine learning algorithms. 

We are going to use the average well known protocol of **machine learning** that is basically the loading of some data and the cleaning and model application upon it. We may use a tokenizer also. Then, we are going to save the model.

## Neural Networks

For this type of work, we may use **Neural Netwoks**, that are specially apt for abstract works. And we'll use LSTM achitecture for the network, as other specific technologies for text interpretation as tokenizers and embeddings. 

### Tokenizers

Tokenizers goes like:

```
#tokenizer
tokenizer = Tokenizer()
tokenizer.fit_on_texts(x_train)
word_index=tokenizer.word_index
total_size = len(word_index)+1
print(total_size)
```

![LSTM basic structure](“images/lstm.png/”)

## Tokenizer

The **tokenizer** is absolutely necessary for this algorithm. Tokenizer is a technology that allows the classification of parts of the text as strings with a semantic value that may be used for the neural network training. It’s a module that permits the creation of lexical  scanner. Since the most important part of the algorithm is the reading by the **Artificial Intelligence** we must use it.

![Tokenizer work](“images/movie-was-good.PNG”)

# Personality-test
Personality test which classifies in four personality types. For the classification is used the natural language processing classification algorithm - Multinomial Naive-Bayes.
The Markov model is used as language model to expand a sentence with its context words for more precision and greater results. 

### Multinomial Naive Bayes
The multinomial NB model, a probabilistic learning method. The probability of a document d being in class c is computed as 
#### result = argmax(c∈ℂ)Pr[c|d] = arg max(c∈ℂ) log Pr[c] + ∑(from k = 1 to n)log Pr[t|dk]

### N-gram Modeling With Markov Chains
Language model (in the narrowest sense) is a probability distribution over a sequence of words (such as a sentence)
The Markov Model is implemented With Jelinek-Mercer interpolated smoothing:
#### Pr̂ int[ xk | x1x2... k - 1 ] = λ#(x1x...xk)/#(x1x2…xk−1∙) + (1 − λ)Pr̂ int[xk | x2x3...xk−1]

## Install
1. Make sure you have GoLang installed on your local machine https://golang.org/doc/install
2. After you successfully install go, run the following command 

    ``` go get github.com/RadostinaIvanova/Personality-test``` 
    
## Running 

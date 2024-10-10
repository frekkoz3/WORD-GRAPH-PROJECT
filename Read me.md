#WORD GRAPH TREE

Iin this repository we want to implement a word graph.
We first will select a wide text (or a collection of text) like all the Linkin Parks lyrics. 
The first approach would be simply to count the "next word occurence", that means that we will create a matrix that count how many time a word follow another one. 
Then we will create a graph from this. 
We will also try to "generate phrases" from this graph. 
(We have no aspectatives from this part).
Then the idea is to, using mainly spacy, tokenize and embeed the words. So we will do the same graph but, this time, we will have position for the words in the space! Since that we would like to try the transofrmer model to see how this space will be squeeze when we will try to "generate phrases".
I would actually like to emphasize the fact that this project is just a personal project done to the main purpose of trying out some nlp concept and frameworks.
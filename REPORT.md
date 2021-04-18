# NLU-Dependency-Grammar-Assignment
First assignment NLU

# REPORT
### Function 1:
#### Extract a path of dependency relations from the ROOT to a token. 
This function takes as input a sentence and return a dictionary whose keys are the tokens of the sentence and the value for each keys is a list, representing the token we encounter from the root of the sentence to the token stored as the key. Each element of the list is a tuple composed by a token and the dependency relation with his head. 

### Fuction 2:
#### Extract subtree of a dependents given a token.
The input of this function is a sentence and the output is a dictionary whose keys are the tokens of the sentence (//the tokens of the sentence matching the token passed as input) and whose value for each key is the list of tokens (//list of token.text?) belonging to the subtree of the token stored as a key, in the order they appear in the sentence.

### Function 3:
#### check if a given list of tokens (segment of a sentence) forms a subtree.
This function takes as input a sentence and a segment of the sentence and returns as output True if the segment forms a subtree of dependencies in the sentence and False if it doesn't. 

### Function 4:
#### identify head of a span, given its tokens.
The input of this function is a list of tokens (not necessarily a sentence) and the output is the head of the span 

### Function 5:
#### extract sentence subject, direct object and indirect object spans.
This function takes as input a sentence and return a dictionary whose keys are tuples consisting of the token and its dependency relation (nsubj for the subject, dobj for the direct object and dative for the indirect object) and the value for each key is the span (//sotto forma di lista di strighe o così?) of the token stored as the first element of the key tuple.
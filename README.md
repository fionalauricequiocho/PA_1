# PA_1
ALPHABET SOUP PROBLEM
def - used for user-defined functions, alphabet_soup - name of function, (word: str): - arguments/input in this case a string
letters - a list to be able to use .sort, list(word) turns string into a list 
letter.sort() - sorts the list
result = "" - empty string to add sorted letter one by one
for in - goes through each character in the sorted list
result += letter - add a letter to the result 
return result - return the final string

EMOTICON PROBLEM
def - used for user-defined functions, emotify - name of function, (sentence: str): - arguments/input in this case a string
return (sentence - return modified version of sentence
.replace - we replace the word to an emoticon

UNPACKING LIST PROBLEM
lst = [1, 2, 3, 4, 5, 6] - creates a list
first = lst[0] - makes index 0 as first 
middle = lst[1 : -1] - slicing ; making index 1 to the index before the last as middle
last = lst[-1] - making the last index as the last

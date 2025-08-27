Programming Assignment 1 – Introduction to Python Programming

Summary

This repository contains solutions to **Experiment 1: Introduction to Python Programming**.
The objective is to apply Python basics in solving problems using **functions, lists, string manipulation, and slicing**.

The problems included are:

1. Alphabet Soup Problem – Rearranging letters of a string alphabetically.
2. Emoticon Problem – Replacing words in a sentence with corresponding emoticons.
3. Unpacking List Problem – Separating a list into first, middle, and last elements.

_____________________________________________________________________________________________________________________________________

Problem Descriptions and Solutions

1. Alphabet Soup Problem

Problem:
Create a function that takes a string and returns a string with its letters in alphabetical order.

Code Snippet:

```python
def alphabet_soup(word: str):
    letters = list(word)   # convert string into list of characters
    letters.sort()         # sort letters alphabetically
    result = ""            # initialize empty string
    for letter in letters:
        result += letter   # concatenate sorted letters
    return result
```

Explanation:

* `def` – defines a user-defined function.
* `alphabet_soup(word: str)` – function name with string input.
* `list(word)` – converts string into a list so it can be sorted.
* `letters.sort()` – sorts the list alphabetically.
* `result = ""` – empty string to collect sorted letters. 
* `for letter in letters:` – loop goes through each sorted character.
* `result += letter` – adds each character to the result.
* `return result` – outputs the final sorted string.

Example Output:

```python
alphabet_soup("hello")   # ➞ 'ehllo'
alphabet_soup("hacker")  # ➞ 'acehkr'
```
_____________________________________________________________________________________________________________________________________

2. Emoticon Problem

Problem:
Create a function that changes specific words (`smile, grin, sad, mad`) into their corresponding emoticons.

Code Snippet:

```python
def emotify(sentence: str):
    return (sentence
        .replace("smile", ":)")
        .replace("grin", ":D")
        .replace("sad", ":(")
        .replace("mad", ">:("))
```

Explanation:

* `def` – defines a user-defined function.
* `emotify(sentence: str)` – function name with string input.
* `.replace("smile", ":)")` – replaces the word with its emoticon.
* Replacements are chained so multiple words can be swapped at once.
* The modified sentence is returned.

Example Output:

```python
emotify("Make me smile")   # ➞ 'Make me :)'
emotify("I am mad")        # ➞ 'I am >:('
```
_____________________________________________________________________________________________________________________________________

3. Unpacking List Problem

Problem:
Unpack a list into three variables: `first`, `middle`, and `last`, with `middle` containing everything in between.

Code Snippet:

```python
lst = [1, 2, 3, 4, 5, 6]

first = lst[0]         # first element
middle = lst[1 : -1]   # slice from second to second-to-last
last = lst[-1]         # last element
```

Explanation:

* `lst = [1, 2, 3, 4, 5, 6]` – creates a list.
* `first = lst[0]` – gets the first element.
* `middle = lst[1:-1]` – slices from index 1 up to before the last element.
* `last = lst[-1]` – gets the last element.

Example Output:

```
first: 1  
middle: [2, 3, 4, 5]  
last: 6
```

_____________________________________________________________________________________________________________________________________

Libraries Used

* Only Python Standard Library was used.
* Core concepts applied: functions, lists, string manipulation, slicing, and replace method.

_____________________________________________________________________________________________________________________________________

Conclusion

This programming assignment highlights fundamental Python concepts. Through solving these problems, I was able to:

8 Define and use functions effectively.
* Practice string manipulation and list operations.
* Apply indexing and slicing to extract values.
* Understand how to break down problems step by step and implement working solutions in Python.




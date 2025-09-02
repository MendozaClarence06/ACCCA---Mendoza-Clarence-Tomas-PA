# ACCCA---Mendoza-Clarence-Tomas-PA-1
This repository is for Mendoza, Clarence's PA-1

# DESCRIPTIONS ABOUT THE ORDER OF CODES USED:

## First code: ALPHABET SOUP PROBLEM:
Create a function that takes a string and returns a string with its letters
in alphabetical order.

## Second code: EMOTICON PROBLEM:
Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon.

## Third code: UNPACKING LIST PROBLEM:
Unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three
variables.

# DESCRIPTION OF FUNCTIONS USED IN MY CODE:

## ALPHABET SOUP PROBLEM:
```
def 'order' - This is to define a working function in the code for use in the notebook.
list() - This function makes the string to a form of list or letters to divide and use the sort function (This is a needed pre-requisite code line)
.sort() - This function then sorts the divided letters to alphabetical order (This is already a built in function and was introduced in our class)
.join() - This function is used to make the letters to one whole string again. "" Was used to ensure there are no spaces in between.
```

## THIS IS FOR EMOTICON PROBLEM:
```
emojis[]- This is a dictionary used with keys and values for their appropriate uses. (For example: smile is equal to ":)")
.split() - This function is used to break the input string to separate number strings.
.get(key, default) - This function checks or gets the words in the input if there are words that are corresponding to particular keys, thus giving back values set.
```

## THIS IS FOR UNPACKING PROBLEM
```
The if not and else conditionals - This condition is used to prevent user mistake. With user mistake like missing spaces for input, the code does not work or function well.
Then, the orders are declared with specifications of position from the input like: order[0] and orde [1,-1] which means all objects from 1 ending before -1, and so on and so forth.
```
# HOW TO USE THE CODE:
Simply input the asked messages and or variables.

Note: These descriptions are all copied from the instructions in PA1 assignment in ACCA UST.

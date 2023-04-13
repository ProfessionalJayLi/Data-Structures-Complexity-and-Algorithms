# Data Structures Complexity and Algorithms Notes

Bruh no way you want this done in a day dawg

``` python

matrix_exam = [
  ['ligma', 'balls', 'this', 'note', 'sucks'],
  ['one', 'day', 'isn\'t', 'enough', 'dawg']
]
print(matrix_exam[0][2], matrix_exam[1][1], matrix_exam[0][4], matrix_exam[0][1])

def square(num):
  return num ** 2

def isEven(num):
  return num % 2 == 0

list1 = [1, 3, 6, 8, 10]
map_exam = list(map(square, list1))

filter_exam = list(filter(isEven, map_exam))  

tuple_exam = (2, 6, 4, 7, 8)
tuple_exam2 = ('holy', "s")

print(tuple_exam[4], tuple_exam2[0])

import random
liste = [random.randint(0, 10) for i in range(0,25)]
set_exam = set(liste)

diction_exam = {
    'race': 'Asian',
    'age': 17,
    'male': True,
    'marital_status': 'Single'
}
print("meet a", diction_exam['marital_status'], diction_exam['age'], diction_exam['race'])

```

## Definitions
  - Matrix: A 2 dimensional array/list (arrays are lists in Java and math). Not an actual data type like str and int, but lists within a list.
    - Rules for coding a matrix:
      -All rows must have same amount of values (if you were to count the amount of values within row 1, it must be the same as row 2 and so on)
      -All columns must have same amount of values (same thing as rows, but vertically :O)
      -Must all be same data type, no switching between (you can't have int and str in the matrix at the same time, same goes for other combinations)
      -Not really a rule, but remember that since a matrix is a list, the first row is considered index 0.
      
  - List Comprehension: A method to creating lists in Python.
    - Requirements:
      -Empty list or one with for loops
      -One or more for loops (range for what might be in your list)
      -Zero or more if statements (depending on how bad you coded the for loops or just because what you want on the list is difficult to produce)
     
  - map(function being used, data): A function that can use a function on iterable data (data that can be indexed). Do not forget to make it into a list using list() as it does not have a set data type.
 
  - filter(function being used, data): Discrimination if it was a function, keeps only the data that returns True with the function. This means function must be able to return boolean (True or False). When AI get too intelligent and overtake civilization we best hope they don't use this stuff in their code.
  
  - Tuples: The cousin of lists (kinda)
    - The benefits of Tuples (a lot of inspiration):
       -Are immutable (can't be changed without recreation like str)
       -It must allow different datatypes as items
       -It must be iterable (indexable)
       -It must be nestable (much like a list within a list)
    - How to use a Tuple:
      -Declared with () as compared to lists which use []
      -() is an empty tuple
      -singleton Tuples are tuples that have only one item, require a comma like this (balls,)
      -Tuples are sliceable; therefore, indexable using square brackets
      
  - Set: Population control set to 1, removes all duplicates within it. Uses {} except when it's empty you use set(). It reorders the data from right to left (outputs the last index first, but when it sees a duplicate it sents those to the end of output)

  - set(data): Noah's Ark as a function but instead of 2 of each it only brings 1.

  - Dictionary: basically a copy cat of class. Uses {} like set but better. "Initializes" using :. It copies attributes by calling it keys, that's more inspiration than what I did for this note.

  - dict(data): turns other data types into dictionaries
    
       

# Python_Excercise

# 1. Length of longest word in list
Complete the function that takes one argument, a list of words, and returns the length of the
longest word in the list.

For example:
['simple', 'is', 'better', 'than', 'complex'] ==> 7
Do not modify the input list.

# 2. Vectors
Create a Vector class with x and y attributes that represent component magnitudes in the x and y directions.
Your vectors should handle vector addition with an .add() method that takes a second vector as an argument and returns a new vector equal to the sum of the vector you call .add() on and the vector you pass in.

For example:
 a = Vector(3, 4)
 
 a.x
 
3

 a.y
 
4

 b = Vector(1, 2)
 
 c = a.add(b)
 
 c.x
 
4

 c.y
 
6

Adding vectors when you have their components is easy: just add the two x components together and the two y components together to get the x and y components for the vector sum.

# 3. Total amount of points

Our football team has finished the championship. Our team's match results are recorded in a collection of strings. Each match is represented by a string in the format "x:y", where x is our team's score and y is our opponents score.

For example: ["3:1", "2:2", "0:1", ...]

Points are awarded for each match as follows:

if x > y: 3 points (win)

if x < y: 0 points (loss)

if x = y: 1 point (tie)

We need to write a function that takes this collection and returns the number of points our team (x) got in the championship by the rules given above.

Notes:
our team always plays 10 matches in the championship

0 <= x <= 4

0 <= y <= 4

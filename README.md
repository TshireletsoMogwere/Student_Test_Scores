Create a function that takes an array of objects where each object represents a student's test score. The object has two properties: name and score. Your function should use the map() function to return a new array of objects with the same structure, but with a new property grade that maps the score to a letter grade based on the following criteria:

90-100: A
80-89: B
70-79: C
60-69: D
Below 60: F


Instructions:

Create a new array of objects using the map() function.
Inside the function passed to map(), use the if...else statement to check each student's score against the grade boundaries.
Return a new object that includes the name, score, and grade properties.

Task:

-Write a program that forms an array of strings from an existing array of strings whose length is less than or equal to 3 characters.
The initial array can be entered from the keyboard, or set at the start of the algorithm execution.
At the same time, it is not recommended to use collections, it is better to do exclusively with arrays;

Description of the solution algorithm:

-First, two arrays are declared: the initial one and the second one of the same length.
Then a method in which the loop is proportional to the length of the array, inside the loop checking the condition ( <=3 ), if yes, the element of the first array is entered in the count element of the second array.
The count variable is used to write from the first array to the second one in turn and so that there are no spaces afterwards.
After assignment, the count variable increases by 1 and returns to the for loop in which i increases by 1.
And so it is checked until the end;
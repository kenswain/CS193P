## Lecture 2 notes

Properties should not be used for interfaces to the application. However they might have some side effects. 

For our project we are going to use a mutable array.

All instance variables in an objective-c object start out as 0.

If you are checking for a null array a great place to do that is placing the check for null in the getter. In this way you can ensure you don't reference a null array.

If an array does not have an object at the address then you can not get it. 

@ with strings are used to turn strings into objects

@ with arrays are used to create the array.

If you implement both the setter and getter you have to use the @synthesize

A + method is a class method not an instance



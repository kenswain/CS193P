## Lecture 3 Notes

Need to search for an eligant solution to the problems that are presented. 

* An example of this is to start with a card face down 
* Another example would be to check for a nill instead of a count for running out of a deck. 
* Brains over braun
* Simple over a big API type solution


During the homework the playing of the game is part of the model

* We will create a class in our model that will contain game play
	* Will not contain any UI
* When designing a class try to design its public API vs the Interface

Objects can have no pubblic setter, but have a private one. This is importaint for things that keep a score.

When you design a program it is often importaint to worry about the model and leave the UI till later. 
You might not even be doing that part as you might hire a designer. 

Start thinking about what will happen as the program expands and if someone else will be using your model. 
Place error checking in your code to hand errors.

Be consistant with what you #define and what you static const as this will make your code more readable.

It is posible to create an outlet to multipul things in the UI

* Use an array for this
* Create a outlet collection for multipul objects
* If you need to decide order you can not use the simple way to collect objects

Primary thing a controler does is syncs model with UI

firstObject and lastObject do not return array out of bounds. They only return the objects or nil


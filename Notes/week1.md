## Week one notes

Need to maybe pickup some CS classes to understand Objective C

Will be writing apps with dozens of classes

iOS7 is still BSD based operating systems

Most of the programing that we will be doing is at the Core Services layer of the stack

Most of the time we will be using Cocoa Touch layer to interact with Apps. 

Dozens of frameworks to learn and focus on. Main ones are going to be Foundation and UIkit

Design strategies and we will focus on MVC (Model view controller)

MVP


   * Split into camps
   * 
      * Model
      * View
      * Controller
   * Most things will sit in the Model such as strategy and logic
   * Controller controls how the models are presented to the user
   * View are the building blocks of the controllers (Generic UI stuff)


Doing MVC right means knowing where things go and how to communicate between elements



   * Controls can always talk to the model
   * 
      * It is unrestricted 
   * Controller to the view is also unrestricted 
   * Model can not talk to view
   * Views can only communicate back to the controller in a structured and blind way
   * 
      * Sends actions when somethings happens
      * 
         * Sometimes the view needs to synchronize with the controller 
         * 
            * Called delegations 
      * Views should not own the data
      * 
         * Data sources are used to present data from controller to the view
         * 
            * Gets from model
            * 
               * Who owns data
   * Model can not talk to controller
   * 
      * Model uses the Radio station concept for letting controller know things have changed
      * 
         * KVO
         * Notification
   * MVC can use as a view another MVC


Objective C



   * Strict superset of C
   * Most important concept of today is Properties
   * All access to the instance veritable is done with a setter method or a getter method 
   * .h is the public API
   * .m is all implementation and private API
   * NSObject is in foundation and is the super class for everything
   * Must import the superclass 
   * All properties can either be strong or weak
   * 
      * Strong means keep it is heap as long as something has a pointer to it
      * Weak means keep it in heap as long as someone has a strong pointer to it
      * 
         * set pointer to weak
   * nonatomic means that calling this is not thread safe
   * Only use dot notation for properties



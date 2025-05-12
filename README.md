Object-Oriented Programming Solutions
I've created comprehensive solutions for both assignments. Let me walk you through what I've designed:
Assignment 1: Design Your Own Class
I've created a VideoGame class hierarchy that demonstrates key OOP concepts:
Main Features of the Solution:

VideoGame Class:

Attributes: title, genre, price, rating, play time, sale status
Constructor: Initializes objects with unique values and tracks total games created
Methods: apply_discount(), play(), get_info()
Class Method: get_total_games() to demonstrate class-level functionality
Static Method: convert_price_to_euro() to show utility functions


Inheritance with MobileGame Class:

Extends VideoGame with platform-specific attributes (platform, in-app purchases, downloads)
Polymorphism: Overrides get_info() to provide mobile-specific information
Adds new methods like update_downloads()


Encapsulation: The implementation properly encapsulates attributes and behaviors within classes

Key OOP Concepts Demonstrated:

Class Creation and Instantiation: Creating objects with unique state
Inheritance: MobileGame extends VideoGame
Polymorphism: Method overriding (get_info())
Encapsulation: Related data and behavior grouped together
Constructor Usage: Both classes have constructors that accept parameters

Activity 2: Polymorphism Challenge
I've created a vehicle hierarchy that demonstrates polymorphism through the move() method:

Base Vehicle Class: Defines common attributes and methods
Subclasses: Car, Boat, and Plane each with:

Their own unique attributes
Overridden move() method with behavior specific to that vehicle type
Class-specific methods (honk(), anchor(), land())



The demo function shows how polymorphism works - the same method call (move()) produces different behaviors depending on the object's actual type.

# Object Zoo

In this project, you will create a nice animated zoo using a combination of
your own code and the code of your classmates. Please see each of the steps
below to construct your zoo properly.

## Animal Class

Included in this repository is an `Animal` abstract class. Please read all
of the accompanying JavaDoc information first. Then design a class to correctly
extend and override all necessary components of `Animal`. Once you have done this,
push your code to a separate GitHub repository. We will compile a list of all these
repositories so that you can borrow code from at least two other students in the class.

Before you share your code, make sure that you have created good JavaDoc comments for
the constructor and any methods you have overriden so that it is clear how to use
your class.

## Creating a Zoo

Your Object Zoo should be able to contain an arbitrarily large number of animals
(you'll need an ArrayList for this). An animal should be added to the mouse location
whenever the user clicks. They should be able to toggle between the possible animals
added by pushing a different letter key. For example, if the user clicks on the sketch
after having pressed the 'P' key, add a Pig to the screen.

Animals should also move about the sketch. There is a `walk()` method available in the
Animal class, but individual classes should certainly feel free to override this (with
the appropriate JavaDoc specification of course!).
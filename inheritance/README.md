# Inheritance Practice

## Create a `User` class.

It should have the following properties...
* `username`, determined by some input
* `password`, determined by some input

It should have the following methods...
* `changePassword`, which allows a user to change his password to some other string

## Create an `Admin` class.

It should inherit from `User`. An admin has the same properties and can run the same methods a user can.

It should also have the following properties...
* `accessLevel`, which is an arbitrary integer determined by some input

It should also have the following methods...
* `overridePassword`, which should take another user and a new password as an argument. When executed, this method changes the password for the passed-in user.

## Bonus I

> Try implementing a class feature we won't be covering in class.

Create a "getter" and "setter" methods for retrieving and updating a user's `username`.

#### References

* Read the "Get & Set" section [here](https://coryrylan.com/blog/javascript-es6-class-syntax).

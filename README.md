# Procedural Abstraction Lab

## Learning Goals

- Practice writing methods.

## Introduction

In this lab, practice writing methods.

Fork and clone this repository. When you do, you will see one file: `Lab.java`.
This assignment consists of some starter code and comments to guide you. Follow
the instructions below.

## Instructions

Assume we are going to take a trip to the fair! The `main()` method has some
sections and comments to help you out. You will need to write the methods to
help describe the trip to the fair.

### Section One

In this section, practice writing simple void methods.

#### rideSwings() method

Write a method to show the user riding the swings.

- This method **must** have the access modifiers `public static`.
- This method will not return anything.
  - Don't forget that if the method doesn't return anything, it still needs a
    return type.
- This method **must** be called `rideSwings`.
- This method will not take in any parameters.
- The method should print "Whee! We're on the swings!"
- Uncomment the first line in "Section One" that calls the `rideSwings()`
  method. Run the program and ensure it works as expected.

### rideFerrisWheel() method

Write a method to show the user riding the ferris wheel a certain number of
times.

- This method **must** have the access modifiers `public static`.
- This method will not return anything.
- This method **must** be called `rideFerrisWheel`.
- This method will take in an `int` parameter to specify the number of times the
  ride will be ridden.
- This method should print "We're riding the ferris wheel x times!"
  - Note that "x" represents the number of times the ride will be ridden.
- This method should loop through the number of times the ferris wheel is to be
  ridden and print "We're riding the ferris wheel!"
  - For example, if the argument passed in is 6, then it should print the
    message "We're riding the ferris wheel!" 6 times. If the argument passed in
    is 3, then it should print the message 3 times.
- Uncomment the second line in "Section One" that calls the `rideFerrisWheel(2)`
  method. Run the program and ensure it works as expected.

Once Section One has been completed, the output of this section should look like
this:

```text
Whee! We're on the swings!
We're riding the ferris wheel!
We're riding the ferris wheel!
```

## Section Two

In this section, write a method with some logic in it.

Write a method to show a user playing a game.

- This method **must** have the access modifiers `public static`.
- This method will not return anything.
- This method **must** be called `playGame`.
- This method will not take in any parameters.
- This method should use the `Random` class to get a `boolean`. The result of
  the pseudorandom `boolean` will determine if the user won the game.
  - Hint: Take a look back at the "If Statement Lab".
- If the user won the game...
  - Print "We are the champions!"
- Else...
  - Print "We lost - oh well. Better luck next time."
- Uncomment the line in "Section Two" that calls the `playGame()` method. Run
  the program and ensure it works as expected.

Once Section Two has been completed, an output of this section could look like
this:

```text
We are the champions!
```

Or it could look like this:

```text
We lost - oh well. Better luck next time.
```

## Section Three

In this section, write a method that returns a value.

### buyFunnelCake() method

- This method **must** have the access modifiers `public static`.
- This method will return a `double`.
- This method **must** be called `buyFunnelCake`.
- This method will not take in any parameters.
- The method should return 5.50 to indicate the price of a funnel cake.
- Uncomment the first line in "Section Three" that calls the `buyFunnelCake()`
  method and the line after that prints the total. Run the program and ensure
  it works as expected.

### buyCornDogs() method

- This method **must** have the access modifiers `public static`.
- This method will return a `double`.
- This method **must** be called `buyCornDogs`.
- This method will take in an `int` value to specify the number of corn dogs
  to be purchased.
- The method should return the number of corn dogs multiplied by 2.25 to
  indicate how much the corn dogs cost.
- Uncomment the rest of the lines of code in "Section Three". Run the program
  and ensure it works as expected.

Once Section Three has been completed, the output of this section should look
like this:

```text
Spent $5.50 on a funnel cake!
Spent a total of $34.75 on fair food!
```

## Expected Output

This is an example of an expected output of the program:

```text
Let's go to the fair!
Whee! We're on the swings!
We're riding the ferris wheel!
We're riding the ferris wheel!
We are the champions!
Spent $5.50 on a funnel cake!
Spent a total of $34.75 on fair food!
```

Here is another example of an expected output of the program:

```text
Let's go to the fair!
Whee! We're on the swings!
We're riding the ferris wheel!
We're riding the ferris wheel!
We lost - oh well. Better luck next time.
Spent $5.50 on a funnel cake!
Spent a total of $34.75 on fair food!
```

Remember, the output when you run it could be either of these since we are
generating a pseudorandom value to determine if the user won or lost the game.

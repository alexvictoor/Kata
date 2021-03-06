Project bootstraped with [Node Flotype Boilerplate](https://github.com/jsynowiec/node-flowtype-boilerplate)

# Mars rover - 3 sessions (1h per session)

The aim of this Kata is to practice:
+ TDD
+ Pair programming
+ Refactoring
+ Simple design
+ Requirement changes
+ Coding standard

If you are thinking about Extreme Programming practices then :thumbsup:.

There are 3 sessions each with a very specific goal

+ implement rules
+ add changes
+ talk about solutions and share feedback

## Rules

+ You are given the initial starting point (x,y) of a rover and the direction (N,S,E,W) it is + facing.
+ The rover receives a character array of commands.
+ Implement commands that move the rover forward/backward (f,b).
+ Implement commands that turn the rover left/right (l,r).
+ Implement wrapping from one edge of the grid to another. (planets are spheres after all)
+ Implement obstacle detection before each move to a new square. If a given sequence of commands encounters an obstacle, the rover moves up to the last possible point and reports the obstacle.

## Changes

+ The set of instructions will be provided from the console
+ Before the rover moves there will be three expected inputs: Size of the world, location and + direction o fthe rover, the full set of commands expected to be carried by the rover. They will + be introduced separately
+ Once all the inputs have been provided, the rover will output on the screen the location after + it moves
+ If there was an obstacle, the mars rover will output the last position before the obstacle and a text saying an obstacle was found.

## Coding standard

+ Name everything (meaningful, searchable, explanatory)
+ No mutable state
+ 2 or fewer function arguments
+ Functions should not take any boolean argument
+ Functional over imperative (no for loops, no let)
+ Encapsulate conditinonals in functions
+ Code should be read from top to bottom with function callers and callee being close


## Ressources

+ [Clean code Javascript](https://github.com/ryanmcdermott/clean-code-javascript)
+ [Katas For Functional Calisthenics](https://codurance.com/2017/11/16/katas-for-functional-calisthenics/#marsroverkata)

## License
Released under MIT license. See the [LICENSE](https://github.com/jsynowiec/node-flowtype-boilerplate/blob/master/LICENSE) file